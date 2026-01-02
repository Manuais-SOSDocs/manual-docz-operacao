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

Nesta etapa, o usuário define **as condições que o sistema irá analisar** para decidir qual classificação deve ser aplicada automaticamente durante a importação.

Funciona como uma regra do tipo:

> _“Se o metadado tiver estas características, então aplique esta classificação.”_

<table data-header-hidden><thead><tr><th width="123">Campo</th><th>Explicação</th></tr></thead><tbody><tr><td><strong>Campo 1 (obrigatório)</strong></td><td><p></p><p>É o <strong>primeiro campo do projeto</strong> que será analisado pelo sistema.</p><ul><li>O usuário escolhe esse campo a partir de uma lista.</li><li>Essa lista é montada automaticamente com base nos <strong>campos cadastrados no projeto</strong>.</li><li>Pelo menos um campo deve ser informado para que a regra funcione.</li></ul><p><em><code>Exemplo: Campo 1 → Tipo Documental</code></em></p></td></tr><tr><td><strong>Valor 1</strong></td><td><p>É o <strong>valor esperado</strong> para o Campo 1.</p><ul><li>O sistema verifica se o valor informado no arquivo de importação corresponde a esse valor.</li><li>Se corresponder, a condição é considerada atendida.</li></ul><p><em><code>Exemplo: Valor 1 → Contrato</code></em></p></td></tr><tr><td><strong>Campo 2 (opcional)</strong></td><td><p>É um <strong>segundo critério</strong>, usado apenas se o usuário quiser tornar a regra mais específica.</p><ul><li>Não é obrigatório.</li><li>Serve para refinar a classificação.</li></ul><p><em><code>Exemplo: Campo 2 → Ano de Produção</code></em></p></td></tr><tr><td><strong>Valor 2</strong></td><td><p>É o valor esperado para o Campo 2.</p><ul><li>A classificação só será aplicada se <strong>as duas condições forem atendidas</strong>.</li><li>Caso o Campo 2 não seja informado, apenas o Campo 1 será considerado.</li></ul><p><em><code>Exemplo: Valor 2 → 2024</code></em></p></td></tr></tbody></table>

</details>

<details>

<summary><mark style="color:$info;"><strong>📌 Como o sistema interpreta essas regras</strong></mark></summary>

* Quando **apenas o Campo 1** estiver configurado, a classificação será aplicada sempre que o valor informado para esse campo for identificado durante a importação.
* Quando **Campo 1 e Campo 2** estiverem configurados, a classificação será aplicada somente quando **ambos os critérios forem atendidos**, tornando a regra mais específica.

</details>

<details>

<summary><mark style="color:$info;"><strong>🔄 Campos carregados automaticamente</strong></mark></summary>

Os campos disponíveis para configuração **não são definidos manualmente**.

Eles são carregados automaticamente de acordo com:

* Os campos cadastrados no projeto selecionado;
* Os campos que estão ativos e válidos no momento da configuração.

Dessa forma, o sistema garante que as regras de classificação sejam criadas apenas com campos realmente existentes no projeto, evitando erros de configuração.

</details>
{% endstep %}

{% step %}
Selecione a classificação que será aplicada quando as condições forem atendidas.

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

<details>

<summary><mark style="color:$info;"><strong>🗂️ Entenda sobre a seleção da Classificação</strong></mark></summary>

Nesta etapa, o usuário deve **selecionar a classificação que será aplicada automaticamente** aos objetos importados quando as condições configuradas forem atendidas.

O campo **Classificação** apresenta as opções disponíveis conforme a **estrutura de classificação definida para o projeto**, baseada na Tabela de Temporalidade e nos parâmetros já configurados.

Ao selecionar uma classificação:

* O sistema entende que **essa será a classificação final** a ser atribuída aos objetos importados;
* Quando as condições definidas nos campos anteriores forem atendidas, a classificação escolhida será aplicada automaticamente;
* Os campos vinculados à classificação (como fases, destinação final, grupo, classe, entre outros) poderão ser **preenchidos de forma automática**, conforme a parametrização do projeto.

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
