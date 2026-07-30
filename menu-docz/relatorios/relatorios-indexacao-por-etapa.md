---
description: MENU > RELATÓRIOS > RELATÓRIOS INDEXAÇÃO POR ETAPA
---

# Relatórios Indexação por Etapa

O relatório de Indexação por Etapa permite acompanhar a evolução dos documentos ao longo do fluxo de tratamento documental, apresentando os registros conforme a etapa documental em que se encontram.

Essa funcionalidade é especialmente útil para monitorar a produtividade das equipes, identificar gargalos operacionais e acompanhar o andamento das atividades de digitalização, indexação, controle de qualidade e integração com outros sistemas.

<figure><img src="../../.gitbook/assets/image (334).png" alt=""><figcaption></figcaption></figure>

### 📊 Como gerar relatórios?

{% stepper %}
{% step %}
Selecione o cliente.
{% endstep %}

{% step %}
Selecione o projeto vinculado ao cliente.
{% endstep %}

{% step %}
Os campos "Tipo" e "Etapa" não precisam ser preenchidos – o sistema os preenche automaticamente.

<table><thead><tr><th width="120.3333740234375">Filtro</th><th>Descrição</th></tr></thead><tbody><tr><td><strong>Cliente</strong></td><td>Define a instituição ou órgão que será considerado na geração do relatório.</td></tr><tr><td><strong>Projeto</strong></td><td>Permite restringir os resultados a um projeto específico.</td></tr><tr><td><strong>Tipo</strong></td><td>Define o tipo de relatório a ser gerado. Neste caso, <em>Relatório - Etapa Indexação</em>.</td></tr><tr><td><strong>Etapa</strong></td><td>Filtra os documentos conforme a etapa documental selecionada.</td></tr><tr><td><strong>Usuário</strong></td><td>Permite consultar os registros vinculados a um usuário específico.</td></tr><tr><td><strong>Data Inicial</strong></td><td>Data inicial do período analisado.</td></tr><tr><td><strong>Data Final</strong></td><td>Data final do período analisado.</td></tr></tbody></table>
{% endstep %}

{% step %}
Se necessário, selecione um usuário interno.
{% endstep %}

{% step %}
Defina o período desejado utilizando os campos de data inicial e final.
{% endstep %}

{% step %}
Clique no botão  ![](<../../.gitbook/assets/image (335).png>) .
{% endstep %}
{% endstepper %}

{% hint style="success" %}
**O download será iniciado automaticamente no desktop.**
{% endhint %}

<details>

<summary><strong>Etapas documentais disponíveis</strong></summary>

<table data-card-size="large" data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><strong>INVENTARIADO</strong></p><p>Indica que o documento foi cadastrado ou inventariado no sistema, mas ainda não iniciou o processo de tratamento documental.</p></td></tr><tr><td><p><strong>INDEXADO</strong></p><p>O documento já possui seus metadados cadastrados e encontra-se indexado no sistema.</p></td></tr><tr><td><p><strong>AGUARDANDO IMAGENS</strong></p><p>O documento foi preparado para processamento, porém as imagens digitais ainda não foram disponibilizadas para continuidade do fluxo.</p></td></tr><tr><td><p><strong>IMAGENS DISPONÍVEIS</strong></p><p>As imagens já foram disponibilizadas e o documento está apto para as próximas etapas de tratamento.</p></td></tr><tr><td><p><strong>LIBERADO PARA AVALIAÇÃO</strong></p><p>O documento foi encaminhado para avaliação em lote por um responsável.</p></td></tr><tr><td><p><strong>AGUARDANDO APROVAÇÃO</strong></p><p>O processo de avaliação foi concluído e o documento aguarda a aprovação.</p></td></tr><tr><td><p><strong>APROVADO</strong></p><p>O documento foi aprovado e está apto para prosseguir no fluxo documental.</p></td></tr><tr><td><p><strong>REPROVADO</strong></p><p>Foram identificadas inconsistências ou pendências que impedem a continuidade do processo, exigindo correção.</p></td></tr><tr><td><p><strong>ASSINADO</strong></p><p>O documento recebeu assinatura digital conforme o fluxo estabelecido.</p></td></tr><tr><td><p><strong>CONCLUÍDO</strong></p><p>Representa o encerramento do fluxo documental. O documento já passou por todas as etapas previstas para o processo.</p></td></tr></tbody></table>

</details>

<details>

<summary><strong>Exemplo de utilização</strong></summary>

No exemplo abaixo, o relatório foi configurado para retornar todos os documentos que se encontram na etapa **INVENTARIADO**, vinculados ao projeto selecionado e processados pelo usuário informado dentro do período definido.

```
Cliente: POCSP-2025
Projeto: PROJETO X
Tipo: Relatório - Etapa Indexação
Etapa: INVENTARIADO
Usuário: ARIEL VIEIRA
Período: 16/05/2026 a 16/06/2026
```

O resultado permitirá identificar todos os documentos que permanecem na etapa de inventário durante o período informado, auxiliando no acompanhamento das atividades e no controle do fluxo documental.

</details>

<details>

<summary><strong>Quando utilizar este relatório?</strong></summary>

* Monitorar a produtividade das equipes de digitalização e indexação;
* Identificar documentos parados em determinada etapa;
* Acompanhar a evolução dos fluxos documentais;
* Validar o cumprimento dos procedimentos operacionais;
* Apoiar auditorias e controles internos;
* Gerar indicadores operacionais de tratamento documental.

> **Importante:** A etapa documental é atualizada automaticamente conforme as ações realizadas no sistema e pode ser utilizada como gatilho para automações, integrações e notificações configuradas no ambiente. Isso foi destacado durante a capacitação como um dos principais mecanismos de controle do fluxo documental.

</details>



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
