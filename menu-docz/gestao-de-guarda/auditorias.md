---
layout:
  width: default
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# Auditorias

O módulo de Auditoria foi desenvolvido para validar a conformidade entre o inventário físico armazenado nos módulos de guarda e as informações registradas no sistema.

Durante o processo de auditoria, o DocZ compara as caixas encontradas fisicamente com os registros existentes no inventário lógico, identificando divergências de localização, caixas ausentes e inconsistências cadastrais. Esse processo permite manter a integridade do acervo, aumentar a confiabilidade das informações e garantir a rastreabilidade das movimentações realizadas na operação de guarda.

A auditoria é envolve três etapas principais:

1. Configuração e abertura da auditoria no DocZ;
2. Execução da auditoria no [Aplicativo](../../aplicativos/app-docz.md) (bipagem e validação física das caixas);
3. Análise dos resultados e tratamento das divergências no DocZ.

<figure><img src="../../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

<details>

<summary>Fluxo da Auditoria</summary>

A auditoria é realizada por módulo de armazenagem e envolve três etapas principais:

1. Abertura da Auditoria;
2. Bipagem e validação física das caixas;
3. Tratamento das divergências identificadas.

```
Gestor habilita auditoria do módulo
↓
Módulo recebe status "Em Auditoria"
↓
Operador realiza a bipagem das caixas
↓
Sistema compara inventário físico x lógico
↓
Identifica conformidades e divergências
↓
Usuário revisa os resultados
↓
Realiza correções ou envia caixas para Transbordo
↓
Auditoria é concluída
```

O modo Auditoria funciona como o gatilho principal para todo o processo. Somente módulos marcados com o status **Em Auditoria** podem ser auditados pelos operadores através do aplicativo.

</details>

<details>

<summary>Status da Auditoria</summary>

Durante o processo, uma auditoria pode assumir os seguintes estados:

| Status                           | Descrição                                                        |
| -------------------------------- | ---------------------------------------------------------------- |
| Em Auditoria                     | Auditoria iniciada e disponível para bipagem das caixas.         |
| Em Auditoria - Bipagem Concluída | Todas as caixas foram bipadas e aguardam revisão dos resultados. |
| Auditado                         | Auditoria concluída e validada.                                  |
| Auditoria Cancelada              | Processo encerrado sem conclusão da auditoria.                   |

Os módulos em auditoria recebem sinalização visual específica no mapa de armazenagem para facilitar sua identificação.

</details>

<details>

<summary>Cenários Identificados pela Auditoria</summary>

Após a bipagem, o sistema realiza automaticamente o cruzamento entre o inventário físico e o inventário lógico.

<table><thead><tr><th width="229.3333740234375">Em Conformidade</th><th>Divergência Lógica sem Física</th><th>Divergência Física em Endereço Incorreto</th></tr></thead><tbody><tr><td>A caixa foi localizada fisicamente e está cadastrada corretamente no mesmo endereço.</td><td>A caixa existe no sistema, porém não foi localizada fisicamente durante a auditoria.</td><td>A caixa foi encontrada fisicamente, porém cadastrada em outro endereço no sistema.</td></tr><tr><td><p><strong>Resultado:</strong></p><ul><li>Status: Em Conformidade</li><li>Nenhuma ação corretiva necessária</li></ul></td><td><p><strong>Resultado:</strong></p><ul><li>Status: Não Localizada</li><li>Pode ser encaminhada para a Área de Transbordo</li><li>Exige confirmação do usuário</li></ul></td><td><p><strong>Resultado:</strong></p><ul><li>Status: Divergente</li><li>Pode ser realocada para o endereço auditado</li><li>Exige confirmação do usuário</li></ul></td></tr></tbody></table>

</details>

<details>

<summary>Área de Transbordo</summary>

A Área de Transbordo é utilizada para gerenciar caixas que apresentaram inconsistências durante a auditoria, especialmente aquelas que não foram encontradas fisicamente em seu endereço lógico esperado.

Nessa área é possível:

* Consultar caixas divergentes;
* Visualizar histórico de auditorias;
* Acompanhar realocações;
* Identificar reincidências;
* Gerar relatórios de ocorrências.

Os principais status são:

<table><thead><tr><th width="224.6666259765625">Status</th><th>Significado</th></tr></thead><tbody><tr><td>Recebida no Transbordo</td><td>Caixa enviada para tratamento após divergência.</td></tr><tr><td>Realocada</td><td>Caixa encontrada e reposicionada corretamente.</td></tr></tbody></table>

</details>

<details>

<summary>Trilha de Auditoria</summary>

Todas as ações executadas durante a auditoria são registradas automaticamente na [**Trilha de Auditoria**](../gestao-de-operacoes/trilha-de-auditoria.md), garantindo rastreabilidade completa das operações.

São registrados eventos como:

<table><thead><tr><th width="271.3333740234375">Evento</th><th>Descrição</th></tr></thead><tbody><tr><td>Início da Auditoria</td><td>Registro da abertura da auditoria de um módulo.</td></tr><tr><td>Finalização da Auditoria</td><td>Registro do encerramento da auditoria.</td></tr><tr><td>Divergência Física x Lógica</td><td>Identificação automática de inconsistências.</td></tr><tr><td>Confirmar Ausência Física</td><td>Confirmação de que uma caixa não foi localizada.</td></tr><tr><td>Enviar para Área de Transbordo</td><td>Registro da movimentação para tratamento.</td></tr><tr><td>Substituída por Outra Caixa</td><td>Registro da substituição quando aplicável.</td></tr></tbody></table>

Cada registro contém:

* Identificador da Auditoria;
* Identificador do módulo auditado;
* Usuário responsável;
* Data e hora da ação;
* Tipo da operação realizada;
* Observações ou justificativas;
* Status anterior;
* Status posterior.

Esse mecanismo permite reconstruir todo o histórico da auditoria e atender requisitos de governança, rastreabilidade e auditoria operacional.

</details>

<details>

<summary>Relatório de Auditorias</summary>

A funcionalidade **Relatório de Auditorias** permite consultar todas as auditorias realizadas nos módulos de armazenagem.

Os filtros disponíveis são:

<table><thead><tr><th width="216.666748046875">Filtro</th><th>Descrição</th></tr></thead><tbody><tr><td>Unidade</td><td>Filtra auditorias por unidade ou galpão.</td></tr><tr><td>Endereço</td><td>Filtra por módulo ou endereço específico.</td></tr><tr><td>Status da Auditoria</td><td>Permite consultar auditorias em andamento, concluídas ou canceladas.</td></tr><tr><td>Usuário Responsável</td><td>Filtra pelo auditor responsável.</td></tr><tr><td>Período</td><td>Restringe a consulta por intervalo de datas.</td></tr></tbody></table>

Os resultados apresentam:

* ID da Auditoria;
* Unidade;
* Endereço auditado;
* Usuário auditor;
* Status;
* Data de início;
* Data de encerramento.

Além da consulta, é possível visualizar os detalhes da auditoria e realizar o download do relatório correspondente.

</details>



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
