---
description: MENU > SOLICITAÇÕES > TODAS AS SOLICITAÇÕES
---

# Todas as Solicitações

Essa tela permite visualizar, filtrar e acompanhar todas as solicitações registradas no sistema, com informações detalhadas sobre tipo, status, solicitante, SLA e tempo decorrido.

<figure><img src="../.gitbook/assets/image (347).png" alt=""><figcaption></figcaption></figure>

### 🧭 **Filtros de Pesquisa (Parte Superior da Tela)**

<table><thead><tr><th width="238">Filtro</th><th>Descrição</th></tr></thead><tbody><tr><td><strong>Tipo de Solicitação</strong></td><td>Escolha entre empréstimo, digitalização, movimentação etc.</td></tr><tr><td><strong>Prioridade da Solicitação</strong></td><td>Filtra por normal, urgente, etc.</td></tr><tr><td><strong>Status SLA</strong></td><td>Permite consultar solicitações dentro ou fora do prazo.</td></tr><tr><td><strong>Tipo de Solicitante</strong></td><td>Interno ou cliente.</td></tr><tr><td><strong>Período (Data Inicial / Final)</strong></td><td>Delimite a busca por data de criação.</td></tr><tr><td><strong>Nº da Solicitação</strong></td><td>Busque por um número específico (sem o “0” inicial e o ano).</td></tr><tr><td><strong>Nº da Etiqueta SOS</strong></td><td>Consulte pelo código de identificação do item.</td></tr></tbody></table>

{% hint style="success" %}
Após preencher os filtros, clique em  ![](<../.gitbook/assets/image (221).png>).
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
  &#xNAN;_“Seu Relatório Analítico de OS foi solicitado com sucesso! Você receberá uma notificação por e-mail assim que o relatório estiver disponível para download.”_
* Para acessá-lo, o usuário deve seguir o caminho: **Menu > Relatórios > Central de Downloads**, onde ficam listados os relatórios gerados em segunda plano.

</details>

<details>

<summary><mark style="color:red;">IMPRIMIR RELATÓRIO OS PDF</mark></summary>

Permite gerar o relatório das solicitações em formato PDF.

</details>



***

### 📥 **Resultados da Pesquisa (Parte Inferior da Tela)**

A grid exibe as solicitações conforme os critérios definidos, com colunas para:

<figure><img src="../.gitbook/assets/image (222).png" alt=""><figcaption></figcaption></figure>

#### **Ações Disponíveis por Solicitação (Última Coluna da Tabela)**

<details>

<summary><img src="../.gitbook/assets/image (223).png" alt="" data-size="original"> Visualizar O.S.</summary>

Permitir o gerenciamento individual dos itens de uma O.S., com ações de atribuição, visualização, impressão e controle de transporte, garantindo rastreabilidade e agilidade na gestão documental.

<figure><img src="../.gitbook/assets/image (224).png" alt=""><figcaption></figcaption></figure>

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

<table><thead><tr><th width="221">Botão</th><th>Função</th></tr></thead><tbody><tr><td><div><figure><img src="../.gitbook/assets/image (13) (1) (1).png" alt=""><figcaption></figcaption></figure></div></td><td>Cancelar o objeto da O.S.</td></tr><tr><td><div><figure><img src="../.gitbook/assets/image (14) (1) (1).png" alt=""><figcaption></figcaption></figure></div></td><td>Para visualizar o objeto da O.S.</td></tr><tr><td><strong>IMPRIMIR LOCALIZAÇÃO GRID</strong></td><td>Gera O.S. digital com a localização do item.</td></tr><tr><td><strong>IMPRIMIR LOCALIZAÇÃO</strong></td><td>Gera O.S. digital com a localização do item.</td></tr><tr><td><strong>ALTERAR ATRIBUIÇÃO DA O.S.</strong></td><td>Permite designar ou redirecionar a O.S. para um usuário interno responsável pelo atendimento.</td></tr><tr><td><strong>IMPRIMIR O.S.</strong></td><td>Faz o download automático da versão digital da O.S.</td></tr><tr><td><strong>DESTINATÁRIOS O.S.</strong></td><td>Adiciona ou consulta os destinatários da O.S. — pessoas que receberão o token e podem acompanhar o andamento da solicitação.</td></tr><tr><td><strong>ACOMPANHAR TRANSPORTE</strong></td><td>Redireciona para a aba de transporte, onde é possível acompanhar a movimentação dos itens.</td></tr><tr><td><strong>VOLTAR</strong></td><td>Fecha a janela pop-up e retorna à tela anterior.</td></tr></tbody></table>

</details>

<details>

<summary><img src="../.gitbook/assets/image (225).png" alt="" data-size="original"> Andamento O.S.</summary>

Exibir o **histórico completo de eventos** relacionados à Ordem de Serviço (O.S.), permitindo rastrear cada etapa do atendimento com clareza e precisão.

<figure><img src="../.gitbook/assets/image (226).png" alt=""><figcaption></figcaption></figure>

#### 🟦 **Ações Disponíveis**

<table><thead><tr><th width="190">Botão</th><th>Função</th></tr></thead><tbody><tr><td><strong>NOVA OCORRÊNCIA</strong></td><td>Adiciona um novo registro sobre acontecimentos durante o atendimento.</td></tr><tr><td><strong>VOLTAR</strong></td><td>Fecha a janela pop-up e retorna à tela anterior.</td></tr></tbody></table>

</details>

<details>

<summary><img src="../.gitbook/assets/image (12) (1) (1).png" alt="" data-size="line">Atender O.S.</summary>

Para **atender uma Ordem de Serviço**, o usuário deve clicar no **ícone correspondente** <img src="../.gitbook/assets/image (12) (1) (1).png" alt="" data-size="original">exibido na grade.\
Em seguida, a OS deve ser **atribuída a um usuário responsável** com **permissão de guarda**.\
Caso necessário, insira uma **observação** e finalize a ação clicando em **Confirmar**.

<figure><img src="../.gitbook/assets/image (10) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><img src="../.gitbook/assets/image (228).png" alt="" data-size="original"> Finalizar O.S.</summary>

Permitir que o usuário **registre a finalização da O.S.** após a conclusão de todas as ações necessárias (entrega, atendimento, transporte, etc.).

<figure><img src="../.gitbook/assets/image (227).png" alt=""><figcaption></figcaption></figure>

#### 🟦 **Ações Disponíveis**

<table><thead><tr><th width="190">Botão</th><th>Função</th></tr></thead><tbody><tr><td><strong>OBSERVAÇÕES</strong></td><td><p>Espaço destinado a registrar informações adicionais relevantes sobre a finalização da solicitação. Pode ser utilizado para indicar:</p><ul><li>Detalhes sobre a entrega;</li><li>Pendências resolvidas;</li><li>Confirmações de recebimento;</li><li>Justificativas de atrasos, entre outros.</li></ul></td></tr><tr><td><strong>CONFIRMAR</strong></td><td>Clique em <strong>Confirmar</strong> para concluir oficialmente a solicitação no sistema.<br><sup><sub>Essa ação atualiza o status da O.S. para</sub><sub> </sub><sub><strong>“Finalizada”</strong></sub><sub>, encerrando o fluxo de atendimento.</sub></sup></td></tr></tbody></table>

</details>

<details>

<summary><img src="../.gitbook/assets/image (229).png" alt="" data-size="original"> Cancelar O.S.</summary>

Permitir que o usuário **cancele uma O.S. que não será mais executada.**

<figure><img src="../.gitbook/assets/image (218).png" alt=""><figcaption></figcaption></figure>

#### 🟦 **Ações Disponíveis**

<table><thead><tr><th width="190">Botão</th><th>Função</th></tr></thead><tbody><tr><td><strong>OBSERVAÇÕES</strong></td><td>Espaço destinado a registrar informações relevantes sobre o cancelamento da solicitação. </td></tr><tr><td><strong>CONFIRMAR</strong></td><td>Clique em <strong>Confirmar</strong> para cancelar oficialmente a solicitação no sistema.</td></tr></tbody></table>

</details>

<details>

<summary><mark style="background-color:green;">Confirmar solicitação</mark></summary>

Após clicar em <img src="../.gitbook/assets/image (220).png" alt="" data-size="original"> , o usuário é direcionado para a tela de **validação por token**.

✅ **Como funciona?**\
O cliente (ou destinatário final) recebe um **código de validação por e-mail**, que deverá ser inserido no sistema para confirmar o **recebimento do objeto**.

<sub><kbd>🔐 Esse processo garante a segurança e rastreabilidade da entrega.<kbd></sub>

<figure><img src="../.gitbook/assets/image (219).png" alt=""><figcaption></figcaption></figure>

**📎 Descubra como validar passo a passo** 👇

[#ordem-de-servico-digital](../pesquisar/como-fazer-solicitacoes-de-objeto.md#ordem-de-servico-digital "mention")

</details>



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
