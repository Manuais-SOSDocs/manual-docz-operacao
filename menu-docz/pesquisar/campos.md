---
hidden: true
icon: list-dropdown
---

# Campos

A tela **Campos** é utilizada para definir os metadados que irão compor a grade de pesquisa e os resultados exibidos no sistema.

Cada objeto exibido na grade apresentará as informações correspondentes aos campos configurados. Quando não houver valor cadastrado para determinado campo, ele será exibido em branco.

O DocZ disponibiliza dois tipos de campos para composição dos metadados: **campos padrão** e **campos personalizados**.

<figure><img src="../../.gitbook/assets/image (428).png" alt=""><figcaption></figcaption></figure>

<table data-card-size="large" data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><strong>Campos Padrão</strong></p><p>Os campos padrão são nativos do sistema e estão vinculados à estrutura interna do banco de dados e às regras de funcionamento da plataforma.<br>Esses campos já vêm pré-configurados e são utilizados por funcionalidades nativas do sistema.</p><p>Suas <strong>regras de negócio não podem ser alteradas pelo usuário</strong>, garantindo a integridade das funcionalidades da aplicação.<br>Entretanto, <strong>sua nomenclatura pode ser personalizada</strong> para melhor adequação à realidade operacional da organização.</p><blockquote><p><strong>Exemplo:</strong> o campo padrão <strong>Identificador SOS</strong> pode ser renomeado para <strong>Número da Etiqueta</strong>, mantendo o mesmo comportamento, finalidade e vínculo com a base de dados.</p></blockquote><p>O sistema disponibiliza os <strong>campos-chave padrão (1 a 11)</strong>, previamente configurados para utilização nos projetos.</p></td></tr><tr><td><p><strong>Campos Personalizados</strong></p><p>Quando os campos padrão não forem suficientes para atender aos requisitos de gestão documental ou às necessidades específicas do negócio, <strong>é possível criar campos personalizados</strong>.</p><p>Esses campos permitem registrar metadados adicionais de acordo com as características da documentação, dos processos de trabalho e das regras da instituição.</p><p>Os campos personalizados podem:</p><ul><li>Ser configurados como obrigatórios ou opcionais;</li><li>Utilizar diferentes tipos de dados (texto, número, data, lista de seleção, entre outros);</li><li>Ser adaptados às necessidades específicas de cada projeto.</li></ul><p><strong>Exemplos de campos personalizados:</strong></p><ul><li>Número do Contrato;</li><li>Fiscal do Contrato;</li><li>Código Patrimonial;<br></li></ul></td></tr></tbody></table>

{% hint style="warning" %}
**Importante lembrar**

Renomear um campo padrão não significa criar um novo campo nem alterar sua lógica de funcionamento. Apenas o nome exibido na interface é modificado, enquanto sua estrutura e comportamento permanecem inalterados.
{% endhint %}

#### Cadastro de Campo

Para criar um novo campo personalizado, preencha as configurações disponíveis na tela **Novo Campo**.

<details>

<summary>Informações Gerais</summary>

<table data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><strong>Nome</strong></p><p>Nome que será exibido para o usuário durante o cadastro, pesquisa e visualização das informações.</p></td></tr><tr><td><p><strong>Descrição</strong></p><p>Texto utilizado para descrever a finalidade do campo.</p></td></tr><tr><td><p><strong>Ordem</strong></p><p>Define a posição de exibição do campo nas telas do sistema.</p></td></tr><tr><td><p><strong>Editável</strong></p><p>Determina se o valor do campo poderá ser alterado após o cadastro.</p></td></tr><tr><td><p><strong>É um dado pessoal</strong></p><p>Identifica que o campo armazena dados pessoais, auxiliando ações relacionadas à LGPD e à governança da informação.</p></td></tr><tr><td><p><strong>É um dado sensível</strong></p><p>Identifica que o campo armazena dados pessoais sensíveis, conforme definido pela LGPD.</p></td></tr><tr><td><p><strong>Pesquisa por terceiros</strong></p><p>Permite que o conteúdo do campo seja utilizado em pesquisas relacionadas a terceiros cadastrados no sistema.</p></td></tr></tbody></table>

</details>

<details>

<summary>Configurações de Guarda</summary>

**Classificação (Guarda)**

Define em qual nível da estrutura documental o campo estará disponível.

Opções disponíveis:

* **Todos**: disponível para todos os níveis.
* **Documento**: disponível apenas para documentos.
* **Caixa-Box**: disponível apenas para caixas-box.
* **Caixa-Arquivo**: disponível apenas para caixas-arquivo.

**Referência (Guarda)**

Permite vincular o campo a uma classificação específica da estrutura documental.

As opções disponíveis variam de acordo com a classificação selecionada.

</details>

<details>

<summary>Formatação</summary>

**Tipo**

Define o formato do dado que será armazenado.

Opções disponíveis:

| Tipo          | Descrição                                                                         |
| ------------- | --------------------------------------------------------------------------------- |
| Texto         | Permite o preenchimento de informações alfanuméricas.                             |
| Número        | Permite apenas valores numéricos.                                                 |
| Data          | Permite o registro de datas.                                                      |
| Between Menor | Utilizado em filtros de pesquisa para definição do valor inicial de um intervalo. |
| Between Maior | Utilizado em filtros de pesquisa para definição do valor final de um intervalo.   |

**Máscara**

Aplica um padrão de preenchimento ao campo.

Opções disponíveis:

| Máscara  | Finalidade                                           |
| -------- | ---------------------------------------------------- |
| CPF      | Formata números de CPF.                              |
| NUP      | Formata números de processos no padrão NUP.          |
| Telefone | Formata números telefônicos.                         |
| Data     | Formata datas conforme padrão definido pelo sistema. |

**Domínio**

Permite associar o campo a uma lista de valores previamente cadastrada, restringindo as opções de preenchimento.

**Mandatório**

Define se o preenchimento do campo será obrigatório durante o cadastro.

</details>

<details>

<summary>Configuração Administrativa</summary>

**Coluna Tabela**

Campo de configuração avançada utilizado para vinculação direta com colunas da base de dados.

{% hint style="warning" %}
**Importante:** esta configuração deve ser utilizada apenas por administradores ou usuários com conhecimento técnico sobre a estrutura do banco de dados do sistema.
{% endhint %}

</details>

<details>

<summary>Retenção de Metadados após Eliminação Documental</summary>

A funcionalidade de retenção de metadados permite definir quais informações deverão permanecer armazenadas após a execução de uma Ordem de Serviço de Expurgo.

O objetivo é garantir rastreabilidade, auditoria e conformidade documental mesmo após a eliminação dos dados e arquivos vinculados ao documento.

**Configuração**

A funcionalidade é configurada em dois níveis complementares:

**1. Configuração do Projeto**

Acesse **Projetos > Editar Projeto** e habilite o parâmetro **Eliminar Dados após Conclusão da O.S. de Expurgo**.

Quando ativado, o sistema passará a executar a eliminação dos dados e arquivos dos documentos após a conclusão da Ordem de Serviço de Expurgo, respeitando as regras de retenção de metadados definidas para o projeto.

**2. Configuração dos Campos**

Após habilitar o parâmetro do projeto, acesse **Projetos > Pesquisar > Campos** e configure individualmente os campos que deverão ser preservados após a eliminação documental.

Para isso, marque o parâmetro **Manter Metadado após Eliminação Documental** nos campos que deverão permanecer armazenados no sistema após o expurgo.

> 📌 **Importante:** somente os campos configurados com esse parâmetro permanecerão disponíveis para consulta, auditoria, relatórios e rastreabilidade após a eliminação dos dados documentais. Os demais metadados serão removidos juntamente com o conteúdo do documento.

**Como funciona?**

Quando o parâmetro **Eliminar Dados após Conclusão da O.S. de Expurgo** estiver habilitado, o sistema executará automaticamente a eliminação dos dados e arquivos dos documentos contemplados pela Ordem de Serviço de Expurgo.

Durante esse processo, serão preservados apenas os campos configurados com a opção **Manter Metadado após Eliminação Documental**.

**Comportamento do Sistema após o Expurgo**

<table data-card-size="large" data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><strong>Campos preservados obrigatoriamente</strong></p><p>Os seguintes campos permanecem armazenados por padrão e não podem ter a retenção desativada:</p><ul><li>Identificador SOS</li><li>Status</li><li>Usuário</li></ul><p>Esses campos garantem a rastreabilidade mínima dos documentos eliminados.</p></td></tr><tr><td><p><strong>Impacto da eliminação</strong></p><p>Após a conclusão do expurgo:</p><ul><li>O status do documento será atualizado para <strong>Expurgado</strong>;</li><li>Os arquivos físicos vinculados ao documento serão removidos;</li><li>Os metadados configurados para retenção permanecerão disponíveis;</li><li>As informações preservadas poderão ser utilizadas em pesquisas, relatórios, auditorias e integrações compatíveis.</li></ul></td></tr><tr><td><p><strong>Auditoria e rastreabilidade</strong></p><p>Todas as operações realizadas durante o processo de eliminação documental são registradas na Trilha de Auditoria.</p><p>Os registros incluem informações como:</p><ul><li>Ordem de Serviço executada;</li><li>Documento afetado;</li><li>Metadados eliminados;</li><li>Metadados preservados;</li><li>Usuário responsável;</li><li>Data e hora da operação.</li></ul></td></tr></tbody></table>

{% hint style="warning" %}
**Atenção**

A preservação de metadados não impede a eliminação dos arquivos físicos do documento. Após o expurgo, o sistema mantém apenas as informações configuradas para retenção, garantindo a rastreabilidade da operação sem preservar o conteúdo documental eliminado.
{% endhint %}

</details>



<a href="./#acoes-disponiveis-localizadas-acima-da-grade-projeto" class="button secondary" data-icon="circle-left">Voltar</a>
