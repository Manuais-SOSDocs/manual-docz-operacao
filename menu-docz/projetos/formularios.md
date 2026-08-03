---
tags:
  - indexacao
  - formularios-de-indexacao
---

# Formulários

O botão **“Formulários”** direciona o usuário para a página de **Formulários de Indexação**, onde são definidos os metadados do projeto.

Nesta seção, é possível **criar, editar e gerenciar formulários** utilizados para a **indexação de documentos**, configurando os campos (metadados) que serão preenchidos durante o cadastro de objetos no sistema.

Cada formulário representa um **modelo de informações estruturadas**, que auxilia o sistema na **localização, classificação e recuperação eficiente** dos documentos, garantindo **organização e rastreabilidade** no processo de gestão.

{% hint style="info" %}
**⚙️ Indexação de Arquivos com Campos Fixos**

Agora é possível **configurar metadados fixos por projeto**, permitindo que determinados campos sejam **preenchidos diretamente na configuração do projeto**.\
Esses metadados permanecem padronizados para todos os formulários vinculados, garantindo **uniformidade e rastreabilidade** nas indexações.

Além disso, os dados configurados como fixos passam a integrar o **relatório analítico de arquivos**, ampliando a **visão gerencial** sobre o acervo e facilitando o controle das informações indexadas.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (3).avif" alt=""><figcaption></figcaption></figure>

**Ações disponíveis:**

<details>

<summary><strong>Criar novo formulário</strong> <img src="../../.gitbook/assets/image (5) (1).png" alt="" data-size="original"></summary>

Ao clicar no ícone **“Novo Formulário”** ![](<../../.gitbook/assets/image (6) (1).png>), localizado na parte superior da tela, o sistema abrirá automaticamente o **painel de criação** no lado direito.

Nesta etapa, todos os campos aparecerão **em branco**, prontos para serem preenchidos conforme os **parâmetros e necessidades do projeto**. Após inserir as informações desejadas, basta salvar para concluir o registro do novo formulário.

Realize a criação e clique em ![](<../../.gitbook/assets/image (7) (1).png>) para confirmar.

</details>

<details>

<summary><strong>Regras de acesso</strong> <img src="../../.gitbook/assets/image (622).png" alt=""></summary>

As regras de acesso aos documentos são definidas no Formulário de Indexação, onde é possível configurar os usuários e grupos autorizados a visualizar ou acessar os documentos associados ao formulário.

#### Para configurar as regras de acesso:

1. Acesse **Projetos > Formulários**.
2. Selecione o formulário desejado ou crie um novo, caso necessário.
3.  Na barra superior da tela, clique no ícone ( ![](<../../.gitbook/assets/image (624).png>) ) **Regras de Acesso**.<br>

    <figure><img src="../../.gitbook/assets/image (623).png" alt=""><figcaption></figcaption></figure>
4.  Na janela exibida, selecione os **grupos** e/ou **usuários** que terão permissão para executar as ações relacionadas ao formulário.<br>

    <figure><img src="../../.gitbook/assets/image (625).png" alt=""><figcaption></figcaption></figure>
5. Clique em **Adicionar** para incluí-los na lista de usuários e grupos autorizados.
6. Salve as alterações.

> **Importante:** As regras de acesso configuradas no formulário são utilizadas pelo DocZ para controlar quais usuários e grupos poderão acessar e executar as operações permitidas nos documentos vinculados a esse Formulário de Indexação.

</details>

<details>

<summary><strong>Editar formulário existente ✏️</strong></summary>

Para editar um formulário já cadastrado, selecione o item desejado na **lista lateral esquerda**.

Ao clicar sobre o **título do formulário**, o sistema exibirá, no painel direito, o **formulário preenchido com os dados originais**. O título da tela será atualizado automaticamente para:

<figure><img src="../../.gitbook/assets/image (10) (1).png" alt=""><figcaption></figcaption></figure>

Realize as alterações necessárias e clique em ![](<../../.gitbook/assets/image (9) (1).png>) para confirmar.

{% hint style="info" %}
**Dica:** Durante a edição, será exibido um **ícone de regras (**![](<../../.gitbook/assets/image (11) (1).png>)**)** ao lado do título. A partir dele, é possível definir as **regras de acesso** e controle de uso do formulário, garantindo maior segurança e personalização.
{% endhint %}

</details>

<details>

<summary><strong>Configuração da Indexação por IA</strong> 🤖</summary>

A habilitação da funcionalidade é realizada pelo administrador do projeto através da configuração dos formulários de indexação.

<figure><img src="../../.gitbook/assets/image (12) (1).png" alt=""><figcaption></figcaption></figure>

{% stepper %}
{% step %}
**Acesso: Projetos → Formulários**
{% endstep %}

{% step %}
Ao criar um novo formulário, o administrador deverá selecionar o tipo:

**Validação de Indexação Extraída por I.A**

Esse novo tipo de formulário é utilizado exclusivamente para os fluxos de validação dos dados extraídos pela Inteligência Artificial.

<figure><img src="../../.gitbook/assets/image (13) (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Para que a funcionalidade seja disponibilizada aos usuários, os seguintes parâmetros devem estar configurados:

<figure><img src="../../.gitbook/assets/image (14) (1).png" alt=""><figcaption></figcaption></figure>

<table data-card-size="large" data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><strong>Etapa Indexação - Entrada</strong></p><p>Define a etapa documental em que o documento será considerado apto para validação.</p><p>Exemplo:</p><ul><li>IA Processada</li><li>Aguardando Validação</li><li>Extração Concluída</li></ul></td></tr><tr><td><p><strong>Etapa Indexação - Saída</strong></p><p>Define a etapa para a qual o documento será encaminhado após a validação.</p><p>Exemplo:</p><ul><li>Validado</li><li>Indexado</li><li>Liberado para Processo</li></ul></td></tr></tbody></table>
{% endstep %}

{% step %}
**Distribuição Aleatória:** Controla a recuperação automática dos documentos para validação.

Quando habilitada, permite que o sistema distribua os documentos automaticamente aos validadores, evitando concorrência entre usuários.
{% endstep %}

{% step %}
Faça a seleção dos caqmpos.

O formulário deve conter todos os campos que poderão ser:

* Extraídos pela IA;
* Revisados pelo usuário;
* Corrigidos durante a validação.

Exemplos:

* Classificação;
* Descrição;
* Número do Processo;
* Data do Documento;
* Interessado;
* Assunto;
* Campos personalizados do projeto.

Todos os campos apresentados ao usuário na tela de validação serão editáveis.
{% endstep %}

{% step %}
O formulário de validação por IA pode ser utilizado nos mesmos contextos já suportados pela indexação tradicional:

* Caixa;
* Documento;
* Arquivo.

A aplicação dependerá da configuração adotada em cada projeto.
{% endstep %}

{% step %}
Após a criação e publicação do formulário, o sistema passa a exibir a opção:

**Validar Extração por IA**

na tela de Indexação para os usuários que possuírem as permissões necessárias.

A partir desse momento, os documentos processados pela Inteligência Artificial poderão seguir o fluxo de validação assistida, combinando automação e conferência humana para garantir maior qualidade dos metadados cadastrados no DocZ.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
Ação realizada com sucesso.
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;"><strong>Entenda o que é o Docfy</strong></mark></summary>

<figure><img src="../../.gitbook/assets/Mais tempo para pensar, menos tempo para digitar..gif" alt=""><figcaption></figcaption></figure>

O Docfy é uma plataforma de Inteligência Artificial aplicada à gestão documental, desenvolvida para automatizar o processamento, a organização e a análise de documentos em larga escala.

Por meio de tecnologias como OCR avançado, Processamento de Linguagem Natural (NLP), Machine Learning e Inteligência Artificial, o Docfy automatiza atividades essenciais da gestão documental, sendo capaz de:

<table data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td>Capturar e processar documentos de diferentes formatos e origens;</td></tr><tr><td>Extrair dados estruturados de forma automática;</td></tr><tr><td>Classificar documentos conforme regras de negócio ou modelos treinados;</td></tr><tr><td>Identificar informações sensíveis e dados pessoais;</td></tr><tr><td>Realizar anonimização e tarjamento de documentos para atendimento à LGPD;</td></tr><tr><td>Disponibilizar mecanismos de busca inteligente para rápida localização de informações.</td></tr></tbody></table>

Com o Docfy, empresas e órgãos públicos transformam grandes volumes de documentos em informações estruturadas e acessíveis, reduzindo custos operacionais, fortalecendo a governança da informação e apoiando decisões mais rápidas e assertivas.

</details>

<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
