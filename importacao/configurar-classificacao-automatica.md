# Configurar classificação automática

Nesta tela, o usuário pode definir regras para que os objetos importados sejam classificados automaticamente, reduzindo o esforço manual e garantindo maior padronização das informações.

{% hint style="info" %}
#### ⚙️ Conceito da Funcionalidade

A Classificação Automática permite que, durante a importação de metadados, o DocZ atribua a classificação correta de forma automática, seguindo regras previamente definidas.

Essas regras permitem:

* Usar **até duas condições** para definir a classificação de cada objeto;
* Relacionar diferentes critérios às classificações disponíveis;
* Aplicar a classificação automaticamente no momento da importação, sem necessidade de ação manual.
{% endhint %}

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>



{% stepper %}
{% step %}
**Menu lateral → Importação → Configurar Classificação Automática**
{% endstep %}

{% step %}
Comece Configurando as Regras

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Escolha o projeto no qual as regras serão aplicadas.

<figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Configure as condições que determinarão a classificação:

* **Campo 1** (obrigatório)
* **Valor 1**
* **Campo 2** (opcional)
* **Valor 2**

<figure><img src="../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

Os campos disponíveis são carregados dinamicamente a partir da configuração do projeto.

<details>

<summary><mark style="color:$info;"><strong>⚙️ Configuração das condições de classificação</strong></mark></summary>

Nesta etapa, você informa ao sistema **quando** uma classificação deve ser aplicada durante a importação.\
Funciona como uma regra simples do tipo:

> _**“Quando o arquivo tiver estas informações, aplicar esta classificação.”**_

Você pode usar **uma ou duas informações** para criar essa regra.

<table data-header-hidden><thead><tr><th width="123">Campo</th><th>Explicação</th></tr></thead><tbody><tr><td><strong>Campo 1 (obrigatório)</strong></td><td><p>Aqui você escolhe <strong>qual informação do arquivo o sistema deve observar primeiro</strong>.</p><ul><li>Esse campo é selecionado a partir de uma lista.</li><li>A lista mostra apenas os <strong>campos que já existem no projeto</strong>.</li><li>Pelo menos um campo precisa ser escolhido para que a regra funcione.</li></ul><p><code>Exemplo: Campo 1 → </code><em><code>Item Documental</code></em></p></td></tr><tr><td><strong>Valor 1</strong><br><strong>(obrigatório)</strong></td><td><p>Depois de escolher o campo, você informa <strong>qual valor esse campo deve ter</strong> para que a regra seja aplicada.</p><ul><li>Durante a importação, o sistema compara o valor do arquivo com o valor informado aqui.</li><li>Se os valores forem iguais, a condição é considerada válida.</li></ul><p><code>Exemplo: Valor 1 → </code><em><code>Contrato</code></em></p><p>👉 Nesse caso, a regra será aplicada sempre que o Tipo Documental for “Contrato”.</p></td></tr><tr><td><strong>Campo 2 (opcional)</strong></td><td><p>Este campo é usado <strong>apenas se o usuário quiser deixar a regra mais específica</strong>.</p><ul><li>Não é obrigatório.</li><li>Serve para adicionar uma segunda condição à regra.</li></ul><p><code>Exemplo: Campo 2 → </code><em><code>Departamento</code></em></p></td></tr><tr><td><strong>Valor 2</strong><br><sup><sub><strong>(obrigatório, caso o "Campo 2" seja preenchido)</strong></sub></sup></td><td><p>Aqui o usuário informa <strong>qual valor o segundo campo deve ter</strong>.</p><ul><li>Quando este campo é utilizado, a classificação só será aplicada se <strong>as duas condições forem atendidas ao mesmo tempo</strong>.</li><li>Se o Campo 2 não for preenchido, o sistema considera apenas o Campo 1.</li></ul><p><code>Exemplo: Valor 2 → </code><em><code>Gestão de contratações</code></em></p></td></tr></tbody></table>

</details>

<details>

<summary><mark style="color:$info;"><strong>📌 Como o sistema interpreta essas regras</strong></mark></summary>

* Quando **apenas o Campo 1** estiver configurado, a classificação será aplicada sempre que o valor informado para esse campo for identificado durante a importação.
* Quando **Campo 1 e Campo 2** estiverem configurados, a classificação será aplicada somente quando **ambos os critérios forem atendidos**, tornando a regra mais específica.
*   Exemplo prático:

    * Se o **Item Documental** for **Contrato**\
      → a classificação será aplicada.
    * Se o **Item Documental** for **Contrato** **e** o **Departamento** for **Gestão de contratações**\
      → a classificação selecionada para a regra será aplicada.

    Caso contrário, a regra não será utilizada.

</details>
{% endstep %}

{% step %}
Selecione a classificação que será aplicada quando as condições forem atendidas.

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

<details>

<summary><mark style="color:$info;"><strong>🗂️ Entenda sobre a seleção da Classificação</strong></mark></summary>

Nesta etapa, o usuário seleciona a **classificação que será aplicada automaticamente** aos objetos importados quando as condições configuradas forem atendidas.

O campo **Classificação** apresenta as opções disponíveis de acordo com a **estrutura de classificação do cliente**, definida com base na Tabela de Temporalidade.

Ao selecionar uma classificação:

* Ela será atribuída automaticamente aos objetos importados quando as condições forem atendidas;
* Os campos relacionados à classificação, como fases, destinação final, grupo e classe, poderão ser **preenchidos automaticamente**, conforme a parametrização do projeto.

</details>
{% endstep %}

{% step %}
Clique em <img src="../.gitbook/assets/image (20).png" alt="" data-size="line"> para registrar a regra.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
Ação concluída, os regras configuradas aparecem na grade abaixo.
{% endhint %}

#### Mais configurações disponiveis:

<figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

<details>

<summary><img src="../.gitbook/assets/image (21).png" alt=""> Editar parâmetros existentes</summary>

{% hint style="warning" %}
Ao editar uma regra, a nova configuração será aplicada **apenas nas próximas importações**.\
As importações realizadas anteriormente **permanecem com a regra que estava vigente no momento da execução**.
{% endhint %}

1. Na parte inferior da tela, localize a **grade de Configurações Disponíveis**, onde são exibidas todas as regras de classificação já cadastradas.
2.  Identifique a regra que deseja alterar e clique no **ícone de edição** correspondente.

    <figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>
3.  Após clicar em editar, a seção **Configurar Classificação Automática**, localizada na parte superior da tela, será carregada automaticamente com os **campos já preenchidos**, conforme os parâmetros definidos no cadastro original da regra.<br>

    <figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>
4. O usuário poderá **alterar os campos, valores ou a classificação**, de acordo com a necessidade.
5. Após realizar as alterações desejadas, clique no botão <img src="../.gitbook/assets/image (27).png" alt="" data-size="line"> para salvar as modificações.

{% hint style="success" %}
Atualização concluída
{% endhint %}

</details>

<details>

<summary><img src="../.gitbook/assets/image (22).png" alt=""> Excluir regras</summary>

{% hint style="warning" %}
Ao excluir uma regra, **ela deixa de ser aplicada nas próximas** importações.\
As **importações realizadas anteriormente permanecem com a regra** que estava vigente no momento da execução.
{% endhint %}

1. Na grade **Configurações Disponíveis**, localize a regra que deseja excluir.
2.  Ao lado do ícone de edição, clique no **ícone “X”**, que representa a ação de exclusão.<br>

    <figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>
3.  Será exibida uma **mensagem de confirmação**.\
    Confirme a ação para prosseguir.<br>

    <figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
Após a confirmação, a regra será **excluída do sistema**.
{% endhint %}

</details>

<details>

<summary>Pesquisar regras específicas</summary>

Na parte inferior da tela, está disponível o campo **Buscar**, que permite localizar rapidamente as regras de classificação já cadastradas.

O usuário pode digitar um termo relacionado à regra desejada, como:

* Nome do projeto
* Campo configurado
* Valor informado
* Classificação aplicada

À medida que o termo é informado, a listagem de **Configurações Disponíveis** é filtrada automaticamente, exibindo apenas os registros que correspondem ao critério de busca.

<figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

</details>

{% hint style="info" %}
#### 🔐 Controle de Acesso

O acesso à configuração de classificação automática é restrito a usuários com permissões específicas. Usuários sem essa autorização não visualizam nem acessam a funcionalidade. Caso seja necessário, o acesso deve ser solicitado ao suporte.
{% endhint %}



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
