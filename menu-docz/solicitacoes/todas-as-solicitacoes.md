---
description: MENU > SOLICITAÇÕES > TODAS AS SOLICITAÇÕES
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

# Todas as Solicitações

Essa tela permite visualizar, filtrar e acompanhar todas as solicitações registradas no sistema, com informações detalhadas sobre tipo, status, solicitante, SLA e tempo decorrido.

<figure><img src="../../.gitbook/assets/image (347).png" alt=""><figcaption></figcaption></figure>

### 🧭 **Filtros de Pesquisa (Parte Superior da Tela)**

<table><thead><tr><th width="238">Filtro</th><th>Descrição</th></tr></thead><tbody><tr><td><strong>Tipo de Solicitação</strong></td><td>Escolha entre empréstimo, digitalização, movimentação etc.</td></tr><tr><td><strong>Prioridade da Solicitação</strong></td><td>Filtra por normal, urgente, etc.</td></tr><tr><td><strong>Status SLA</strong></td><td>Permite consultar solicitações dentro ou fora do prazo.</td></tr><tr><td><strong>Tipo de Solicitante</strong></td><td>Interno ou cliente.</td></tr><tr><td><strong>Período (Data Inicial / Final)</strong></td><td>Delimite a busca por data de criação.</td></tr><tr><td><strong>Nº da Solicitação</strong></td><td>Busque por um número específico (sem o “0” inicial e o ano).</td></tr><tr><td><strong>Nº da Etiqueta SOS</strong></td><td>Consulte pelo código de identificação do item.</td></tr></tbody></table>

{% hint style="success" %}
Após preencher os filtros, clique em  ![](<../../.gitbook/assets/image (221).png>).
{% endhint %}

### 📊 Mais ações - Relatórios de Soliciatções:

<details>

<summary><mark style="color:green;">IMPRIMIR RELATÓRIO OS EXCEL</mark></summary>

Exporta para o computador do usuário os dados do painel de solicitações em formato Excel.

</details>

<details>

<summary><mark style="color:green;">IMPRIMIR RELATÓRIO OS DE SUPRIMENTO</mark></summary>

Gera um relatório específico com informações sobre as solicitações de suprimentos do projeto em formato Excel.

</details>

<details>

<summary><mark style="color:green;">IMPRIMIR RELATÓRIO ANALÍTICO DE OS</mark></summary>

Apresenta um relatório detalhado das Ordens de Serviço.

* O relatório é gerado em _background_ e o usuário será notificado por e-mail quando estiver disponível para download.
* Após a solicitação, será exibida a mensagem:\
  _“Seu Relatório Analítico de OS foi solicitado com sucesso! Você receberá uma notificação por e-mail assim que o relatório estiver disponível para download.”_
* Para acessá-lo, o usuário deve seguir o caminho: **Menu > Relatórios > Central de Downloads**, onde ficam listados os relatórios gerados em segunda plano.

</details>

<details>

<summary><mark style="color:red;">IMPRIMIR RELATÓRIO OS PDF</mark></summary>

Permite gerar o relatório das solicitações em formato PDF.

</details>

***

### 📥 **Resultados da Pesquisa (Parte Inferior da Tela)**

A grid exibe as solicitações conforme os critérios definidos, com colunas para:

<figure><img src="../../.gitbook/assets/image (641).png" alt=""><figcaption></figcaption></figure>

#### **Ações Disponíveis por Solicitação (Última Coluna da Tabela)**

<details>

<summary><img src="../../.gitbook/assets/image (223).png" alt="" data-size="original"> Visualizar O.S.</summary>

Permitir o gerenciamento individual dos itens de uma O.S., com ações de atribuição, visualização, impressão e controle de transporte, garantindo rastreabilidade e agilidade na gestão documental.

<figure><img src="../../.gitbook/assets/image (648).png" alt=""><figcaption></figcaption></figure>

#### Entenda o que significa cada campo:

* **Item:** apresenta o identificador SOS do objeto solicitado.
* **Descrição:** exibe as informações do metadado indexado.
* **Motivo:** campo destinado ao registro da justificativa da solicitação.
* **Quantidade:** indica o número de objetos solicitados.
* **Status:** mostra a validação do item durante o atendimento.

🔹 ⚠️ — indica que o item **ainda não foi validado**, ou seja, **não está pronto para o atendimento**.\
🔹 **✔️ (check)** — indica que o item **foi validado e separado para atendimento**.

* **Doc. Principal:** identifica se o item é o **documento principal** dentro do conjunto de objetos solicitados.

***

#### 🟦 **Ações Disponíveis**

<table><thead><tr><th width="221">Botão</th><th>Função</th></tr></thead><tbody><tr><td><div><figure><img src="../../.gitbook/assets/image (13) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div></td><td>Cancelar o objeto da O.S.</td></tr><tr><td><div><figure><img src="../../.gitbook/assets/image (14) (1) (1) (1).png" alt=""><figcaption></figcaption></figure></div></td><td>Para visualizar o objeto da O.S.</td></tr><tr><td><strong>IMPRIMIR LOCALIZAÇÃO GRID</strong></td><td>Gera O.S. digital com a localização do item.</td></tr><tr><td><strong>IMPRIMIR LOCALIZAÇÃO</strong></td><td>Gera O.S. digital com a localização do item.</td></tr><tr><td><strong>ALTERAR ATRIBUIÇÃO DA O.S.</strong></td><td>Permite designar ou redirecionar a O.S. para um usuário interno responsável pelo atendimento.</td></tr><tr><td><strong>IMPRIMIR O.S.</strong></td><td>Faz o download automático da versão digital da O.S.</td></tr><tr><td><strong>DESTINATÁRIOS O.S.</strong></td><td>Adiciona ou consulta os destinatários da O.S. — pessoas que receberão o token e podem acompanhar o andamento da solicitação.</td></tr><tr><td><strong>ACOMPANHAR TRANSPORTE</strong></td><td>Redireciona para a aba de transporte, onde é possível acompanhar a movimentação dos itens.</td></tr><tr><td><strong>EXPORTAR ARQUIVOS DE DESTINAÇÃO</strong></td><td><p>A funcionalidade permite gerar um pacote contendo os arquivos vinculados às Ordens de Serviço de <strong>Expurgo</strong>, <strong>Recolhimento</strong> e <strong>Saída Definitiva</strong>.</p><ul><li><em>O sistema encaminhará a solicitação para processamento na <strong>Central de Downloads</strong>.</em></li></ul></td></tr><tr><td><strong>VOLTAR</strong></td><td>Fecha a janela pop-up e retorna à tela anterior.</td></tr></tbody></table>

</details>

<details>

<summary><img src="../../.gitbook/assets/image (225).png" alt="" data-size="original"> Andamento O.S.</summary>

Exibir o **histórico completo de eventos** relacionados à Ordem de Serviço (O.S.), permitindo rastrear cada etapa do atendimento com clareza e precisão.

<figure><img src="../../.gitbook/assets/image (226).png" alt=""><figcaption></figcaption></figure>

#### 🟦 **Ações Disponíveis**

<table><thead><tr><th width="190">Botão</th><th>Função</th></tr></thead><tbody><tr><td><strong>NOVA OCORRÊNCIA</strong></td><td>Adiciona um novo registro sobre acontecimentos durante o atendimento.</td></tr><tr><td><strong>VOLTAR</strong></td><td>Fecha a janela pop-up e retorna à tela anterior.</td></tr></tbody></table>

</details>

<details>

<summary><img src="../../.gitbook/assets/image (12) (1) (1) (1).png" alt="" data-size="line">Atender O.S.</summary>

Para **atender uma Ordem de Serviço**, o usuário deve clicar no **ícone correspondente** <img src="../../.gitbook/assets/image (12) (1) (1) (1).png" alt="" data-size="original">exibido na grade.\
Em seguida, a OS deve ser **atribuída a um usuário responsável** com **permissão de guarda**.\
Caso necessário, insira uma **observação** e finalize a ação clicando em **Confirmar**.

<figure><img src="../../.gitbook/assets/image (10) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><img src="../../.gitbook/assets/image (228).png" alt="" data-size="original"> Finalizar O.S.</summary>

Permitir que o usuário **registre a finalização da O.S.** após a conclusão de todas as ações necessárias (entrega, atendimento, transporte, etc.).

<figure><img src="../../.gitbook/assets/image (227).png" alt=""><figcaption></figcaption></figure>

#### 🟦 **Ações Disponíveis**

<table><thead><tr><th width="190">Botão</th><th>Função</th></tr></thead><tbody><tr><td><strong>OBSERVAÇÕES</strong></td><td><p>Espaço destinado a registrar informações adicionais relevantes sobre a finalização da solicitação. Pode ser utilizado para indicar:</p><ul><li>Detalhes sobre a entrega;</li><li>Pendências resolvidas;</li><li>Confirmações de recebimento;</li><li>Justificativas de atrasos, entre outros.</li></ul></td></tr><tr><td><strong>CONFIRMAR</strong></td><td>Clique em <strong>Confirmar</strong> para concluir oficialmente a solicitação no sistema.<br><sup><sub>Essa ação atualiza o status da O.S. para</sub><sub> </sub><sub><strong>“Finalizada”</strong></sub><sub>, encerrando o fluxo de atendimento.</sub></sup></td></tr></tbody></table>

</details>

<details>

<summary><img src="../../.gitbook/assets/image (229).png" alt="" data-size="original"> Cancelar O.S.</summary>

Permitir que o usuário **cancele uma O.S. que não será mais executada.**

<figure><img src="../../.gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>

#### 🟦 **Ações Disponíveis**

<table><thead><tr><th width="190">Botão</th><th>Função</th></tr></thead><tbody><tr><td><strong>OBSERVAÇÕES</strong></td><td>Espaço destinado a registrar informações relevantes sobre o cancelamento da solicitação. </td></tr><tr><td><strong>CONFIRMAR</strong></td><td>Clique em <strong>Confirmar</strong> para cancelar oficialmente a solicitação no sistema.</td></tr></tbody></table>

{% hint style="info" %}
[Acesse aqui a gestão de O.S. canceladas](solicitacoes-canceladas.md)
{% endhint %}

</details>

<details>

<summary><mark style="background-color:blue;">Impressão em lote</mark></summary>

A funcionalidade **Impressão em Lote** permite gerar, de uma única vez, arquivos relacionados a várias Ordens de Serviço, evitando a necessidade de realizar a impressão individualmente.

O recurso está disponível nas telas:

* **Solicitações > Todas as Solicitações**;
* **Solicitações > Solicitações Abertas**;
* **Solicitações > Solicitações em Andamento**.

> **Dica:** ao acessar **Todas as Solicitações**, recomenda-se utilizar os filtros disponíveis para localizar as O.S. de acordo com o status ou outras informações desejadas antes de iniciar a impressão em lote.

#### Como realizar a impressão em lote

1. Acesse uma das telas de solicitações disponíveis;
2. Localize as Ordens de Serviço que deseja incluir na impressão;
3.  Clique no botão **Impressão em Lote**, localizado abaixo da grade de resultados;<br>

    <figure><img src="../../.gitbook/assets/image (645).png" alt=""><figcaption></figcaption></figure>
4. Na janela **Impressão em Lote de O.S.**, selecione o **Tipo de Relatório** que deseja gerar:
   * **Imprimir Localização Grid**;
   * **Imprimir Localização**;
   * **Imprimir O.S.**;
5.  Na seção **Ordens de Serviço Disponíveis**, selecione as O.S. que deseja incluir no arquivo. Também é possível utilizar a opção **Selecionar todas as Ordens de Serviço**;<br>

    <figure><img src="../../.gitbook/assets/image (646).png" alt=""><figcaption></figcaption></figure>
6. Clique em **Exportar**.

Após a solicitação de exportação, o sistema exibirá uma mensagem informando que a impressão em lote foi iniciada.

<figure><img src="../../.gitbook/assets/image (647).png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
**O arquivo será disponibilizado na** [**Central de Downloads**](../relatorios/central-de-downloads.md)**, e o usuário também será notificado por e-mail quando o processamento for concluído.**
{% endhint %}

</details>

<details>

<summary><mark style="background-color:green;">Confirmar solicitação</mark></summary>

Após clicar em <img src="../../.gitbook/assets/image (220).png" alt="" data-size="original"> , o usuário é direcionado para a tela de **validação por token**.

✅ **Como funciona?**\
O cliente (ou destinatário final) recebe um **código de validação por e-mail**, que deverá ser inserido no sistema para confirmar o **recebimento do objeto**.

<sub><kbd>🔐 Esse processo garante a segurança e rastreabilidade da entrega.<kbd></sub>

<figure><img src="../../.gitbook/assets/image (219).png" alt=""><figcaption></figcaption></figure>

**📎 Descubra como validar passo a passo** 👇

[#ordem-de-servico-digital](../pesquisar/como-fazer-solicitacoes-de-objeto.md#ordem-de-servico-digital "mention")

</details>

<details>

<summary>Exportação de Arquivos de Destinação</summary>

A funcionalidade **Exportação de Arquivos de Destinação** permite gerar um pacote contendo os arquivos vinculados às Ordens de Serviço de **Expurgo**, **Recolhimento** e **Saída Definitiva**.

O recurso é utilizado quando há necessidade de transferir, recolher ou disponibilizar documentos relacionados a processos de destinação documental, mantendo a rastreabilidade e o controle das operações realizadas.

![](https://manualsosdocs.gitbook.io/adm-docz/~gitbook/image?url=https%3A%2F%2F2165951091-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FH2zBMzYHjbRsfnTeRGr3%252Fuploads%252F8YCX4FUANkMZu6Qi8qr4%252Funknown.png%3Falt%3Dmedia%26token%3D221e35b7-10f7-433a-ae4c-e6b2356a1f2f\&width=768\&dpr=3\&quality=100\&sign=f4e50c2d\&sv=2)

**Como exportar os arquivos**

1. Acesse **Solicitações > Todas as Solicitações**.
2. Localize a Ordem de Serviço desejada.
3. Clique no ícone de **Lupa** para visualizar os detalhes da solicitação.
4. Clique no botão **Exportar Arquivos de Destinação**.
5. O sistema encaminhará a solicitação para processamento na **Central de Downloads**.

Após a conclusão do processamento, o pacote estará disponível para download seguindo o mesmo padrão utilizado na funcionalidade de download em lote do sistema.

**Tipos de Solicitação Compatíveis**

A exportação está disponível apenas para Ordens de Serviço dos tipos:

* Expurgo;
* Recolhimento;
* Saída Definitiva.

**Processamento da Exportação**

Ao solicitar a exportação, o sistema:

* Identifica automaticamente os objetos vinculados à Ordem de Serviço;
* Reúne os arquivos associados aos documentos selecionados;
* Gera o pacote de exportação de forma assíncrona;
* Disponibiliza o resultado na Central de Downloads.

**Rastreabilidade**

Todas as exportações realizadas são registradas automaticamente no sistema, incluindo:

* Usuário responsável pela solicitação;
* Data e hora da operação;
* Ordem de Serviço relacionada;
* Registro na Trilha de Auditoria;
* Histórico de ocorrências da solicitação.

> Importante: documentos sem arquivos vinculados não impedem a geração da exportação. Nesses casos, o sistema processa normalmente os demais itens e registra a ocorrência para fins de rastreabilidade.

</details>

<details>

<summary>Integração entre Transporte e Ordem de Serviço</summary>

Quando uma Ordem de Serviço estiver vinculada a um transporte, as principais movimentações realizadas durante o processo logístico serão registradas automaticamente no histórico da própria O.S.

Essa integração permite acompanhar o andamento do transporte diretamente pela solicitação, sem necessidade de acessar o módulo de Gestão de Transporte.

**Ocorrências registradas automaticamente**

As seguintes ações realizadas no transporte geram registros automáticos no histórico da Ordem de Serviço vinculada:

| Ação no Transporte | Registro na O.S.      |
| ------------------ | --------------------- |
| Atender            | Transporte Iniciado   |
| Atrasado           | Transporte Atrasado   |
| Cheguei            | Transporte no Local   |
| Finalizar          | Transporte Finalizado |
| Cancelar           | Transporte Cancelado  |

**Informações registradas**

Cada ocorrência adicionada ao histórico da Ordem de Serviço contém:

* Usuário responsável pela ação;
* Data e hora da ocorrência;
* Tipo da ocorrência;
* Observações registradas durante a operação;
* Referência ao transporte de origem.

**Vínculo com o transporte**

O campo **Observação** passa a exibir automaticamente uma referência ao transporte responsável pela movimentação.

Exemplos:

**Quando existe observação preenchida:**

> Coleta realizada com sucesso | Transporte 000123/2026

**Quando não existe observação:**

> Transporte 000123/2026

O identificador do transporte é exibido como um link clicável, permitindo acesso direto ao registro correspondente na Gestão de Transporte.

{% hint style="info" %}
**Importante**

* Os registros são criados apenas para a Ordem de Serviço associada ao item movimentado.
* Caso um transporte possua várias Ordens de Serviço vinculadas, cada ocorrência será registrada somente na O.S. efetivamente impactada pela ação executada.
{% endhint %}

</details>



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
