---
description: MENU > RELATÓRIOS > RELATÓRIOS PADRÃO
---

# Relatórios Padrão

<figure><img src="../.gitbook/assets/image (270).png" alt=""><figcaption></figcaption></figure>

A interface apresenta os seguintes campos de preenchimento para geração de relatórios:

<table><thead><tr><th width="152.181884765625">CAMPO</th><th width="549.4544067382812">DESCRIÇÃO</th></tr></thead><tbody><tr><td>Cliente</td><td>Selecione o cliente desejado.</td></tr><tr><td>Projeto</td><td>Lista de projetos vinculados ao cliente selecionado.</td></tr><tr><td>Tipo</td><td>Escolha o tipo de relatório que deseja gerar.</td></tr><tr><td>Gerar Relatórios sem Objetos Não Implantados</td><td>Marque se quiser incluir dados de objetos ainda não implantados.</td></tr><tr><td>Data Pesquisa</td><td>Selecione o campo de data a ser considerado. (ex: criação, atualização)</td></tr><tr><td>Data Inicial e Data Final</td><td>Defina o intervalo de datas que o relatório deve abranger.</td></tr><tr><td>Botão “<mark style="color:green;">Gerar Relatório</mark>”</td><td>Inicia a criação do relatório com base nos filtros aplicados.</td></tr></tbody></table>

## Passo a passo para gerar um relatório

{% stepper %}
{% step %}
**Acesse no menu lateral a opção  `Relatórios`  >  `Relatórios Padrão`**
{% endstep %}

{% step %}
No campo **Cliente**, clique e selecione o cliente desejado.
{% endstep %}

{% step %}
Em **Projeto**, selecione um ou mais projetos vinculados ao cliente.
{% endstep %}

{% step %}
No campo **Tipo**, escolha o tipo de relatório que deseja gerar.

|                                                         |                                                                                                           |                                                                    |
| ------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| **Relatório – Caixas**                                  | Apresenta todas as caixas cadastradas no sistema, com informações de identificação, status e localização. | Para controle físico, localização e conferência de caixas.         |
| **Relatório – Documentos**                              | Lista os documentos cadastrados, com seus respectivos metadados e vínculos.                               | Para consulta geral, inventário e conferência documental.          |
| **Relatório – Expurgo / Saída Definitiva**              | Exibe documentos e caixas que passaram por eliminação ou saída definitiva.                                | Para auditoria, comprovação legal e controle de descarte.          |
| **Relatório Estatístico – Solicitação**                 | Apresenta dados estatísticos sobre solicitações realizadas no sistema.                                    | Para análise de demanda, uso do acervo e atendimento aos usuários. |
| **Relatório Estatístico – Tipo de Objeto**              | Agrupa os registros por tipo de objeto (documento, caixa, etc.).                                          | Para entender a composição e volume do acervo.                     |
| **Relatório Estatístico – Status do Objeto**            | Mostra a distribuição dos objetos por status (ativo, arquivado, eliminado, etc.).                         | Para controle operacional e acompanhamento do acervo.              |
| **Relatório Estatístico – Status de Gestão Documental** | Exibe estatísticas conforme as fases da gestão documental.                                                | Para análise arquivística e planejamento da gestão documental.     |
| **Relatório Estatístico – Tipo de Objeto e Status**     | Combina tipo de objeto e status em uma visão cruzada.                                                     | Para análises detalhadas e gerenciais do acervo.                   |
| **Relatório – Dinâmico**                                | Permite personalização de filtros e campos conforme a necessidade do usuário.                             | Para relatórios sob demanda e análises específicas.                |
| **Relatório – Relacionamento entre Objetos**            | Mostra o vínculo entre documentos, caixas e demais objetos.                                               | Para rastreabilidade e entendimento da estrutura documental.       |
{% endstep %}

{% step %}
Se desejar incluir itens ainda não implantados, marque a opção **Gerar Relatórios sem Objetos Não Implantados** ![](<../.gitbook/assets/image (294).png>).
{% endstep %}

{% step %}
Em **Data Pesquisa**, selecione o tipo de data a ser considerada na filtragem.

<figure><img src="../.gitbook/assets/image (298).png" alt=""><figcaption></figcaption></figure>

|                                   |                                                               |                                                                            |
| --------------------------------- | ------------------------------------------------------------- | -------------------------------------------------------------------------- |
| **Data Criação**                  | Data em que o registro foi criado no sistema DocZ.            | Para identificar quando documentos, caixas ou objetos foram cadastrados.   |
| **Data Atualização**              | Data da última alteração realizada no registro.               | Para auditoria, controle de mudanças e acompanhamento de ajustes recentes. |
| **Data Distribuição**             | Data em que o objeto foi distribuído ou encaminhado no fluxo. | Para monitorar movimentações e prazos de distribuição.                     |
| **Data Indexação Inicial**        | Data em que o documento iniciou o processo de indexação.      | Para análise de produtividade e início do tratamento documental.           |
| **Data Indexação Final**          | Data de conclusão da indexação do documento.                  | Para verificar finalização do tratamento documental.                       |
| **Data Catalogação Complementar** | Data em que foi realizada a catalogação complementar.         | Para controle de enriquecimento e padronização de metadados.               |
| **Data Implantação**              | Data em que o registro foi implantado ou ativado no sistema.  | Para relatórios de implantação, migração ou entrada oficial em produção.   |
{% endstep %}

{% step %}
Preencha os campos de **Data Inicial** e **Data Final** com o período desejado.
{% endstep %}

{% step %}
Clique no botão ![](<../.gitbook/assets/image (296).png>) no canto inferior direito da grid.
{% endstep %}

{% step %}
Após clicar, o sistema solicitará o formato do arquivo:  **`.xlsx`**  (Excel)  **`.csv`**  (planilha simples). E depois clique em  ![](<../.gitbook/assets/image (299).png>)

<figure><img src="../.gitbook/assets/image (300).png" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

{% hint style="success" %}
O sistema gerará automaticamente o relatório e fará o download no formato escolhido direto para seu computador.
{% endhint %}



<a href="./" class="button secondary" data-icon="circle-left">Retornar para anterior</a>
