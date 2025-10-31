---
description: Seleção e Detalhamento de Projetos
icon: folder-open
---

# PROJETOS

A interface está dividida em **duas seções principais:**

### Grade localizada no lado Esquerdo: Selecione o Projeto

<figure><img src="../.gitbook/assets/image (279).png" alt=""><figcaption></figcaption></figure>

### Grade localizada no lado direito: Projeto

Após clicar no ícone <img src="../.gitbook/assets/image (276).png" alt="" data-size="line"> na esquerda, a grade da direita exibe os **detalhes completos** do projeto selecionado, como:

<figure><img src="../.gitbook/assets/image (275).png" alt=""><figcaption></figcaption></figure>

### Detalhes – Ações disponíveis na parte superior:

<figure><img src="../.gitbook/assets/image (466).png" alt=""><figcaption></figcaption></figure>

<details>

<summary><img src="../.gitbook/assets/image (280).png" alt="" data-size="line"> SLA Projeto</summary>

A tela de **SLA (Service Level Agreement)** é responsável pelo gerenciamento das regras que determinam os prazos de execução para diferentes tipos de solicitações no sistema **DocZ**.\
Por meio dessa interface, o usuário pode **cadastrar, visualizar, editar e filtrar** SLAs conforme as necessidades operacionais e contratuais.

#### **Estrutura da Tela**

A tela de **SLA (Acordo de Nível de Serviço)** é dividida em **duas seções principais**, que permitem configurar, visualizar e ajustar regras de prazo para diferentes tipos de solicitações.

**1. Formulário de Cadastro e Filtro (parte superior)**

Nesta área, o usuário pode **criar novas regras** ou **filtrar SLAs existentes**, definindo os parâmetros que determinam o tempo de execução das solicitações.

Os campos disponíveis são:

<table data-header-hidden><thead><tr><th width="186"></th><th></th></tr></thead><tbody><tr><td><strong>Campo</strong></td><td><strong>Descrição</strong></td></tr><tr><td><strong>Código</strong></td><td>Identificador único da regra.</td></tr><tr><td><strong>Tipo de Solicitação</strong></td><td>Define o serviço (ex.: Digitalização, Cópia, Empréstimo).</td></tr><tr><td><strong>Prioridade</strong></td><td>Indica o nível de urgência (<em>Normal</em> ou <em>Urgente</em>).</td></tr><tr><td><strong>Prazo</strong></td><td>Define o tempo máximo para conclusão. Aceita valores de até <strong>300 horas</strong>, permitindo flexibilidade para atividades complexas ou de longa duração.</td></tr><tr><td><strong>Unidade de Origem</strong></td><td>Identifica a unidade responsável pela solicitação.</td></tr><tr><td><strong>Local de Destino da O.S.</strong></td><td>Permite configurar o prazo considerando tanto a origem quanto o destino da solicitação, tornando o controle mais preciso.</td></tr><tr><td><strong>Regra para Abertura de O.S. após as 11h</strong></td><td>Aplica condições específicas para solicitações abertas após as 11h.</td></tr></tbody></table>

Após preencher as informações, basta clicar em <img src="../.gitbook/assets/image (449).png" alt="" data-size="line"> para salvar a configuração.

**2. Lista de SLAs Cadastrados (parte inferior)**

A tabela exibe todas as regras cadastradas, facilitando o acompanhamento e a manutenção das configurações.

O sistema permite **editar diretamente os prazos na própria tabela**, agilizando ajustes e garantindo mais praticidade no gerenciamento.\
Também estão disponíveis ações para **inativar** regras conforme a necessidade.

<figure><img src="../.gitbook/assets/image (434).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><img src="../.gitbook/assets/image (281).png" alt="" data-size="line"> Permissão de Acesso</summary>

A tela **“Demonstração”** permite gerenciar quais usuários têm permissão para acessar e visualizar um projeto específico. A interface é dividida em **duas seções interativas principais**:

<figure><img src="../.gitbook/assets/image (435).png" alt=""><figcaption></figcaption></figure>

#### **1. Bloco "Selecione os Usuários"**

O bloco é **expansível**: inicialmente aparece compacto e, ao clicar, mostra a lista completa de usuários disponíveis no sistema.

Antes de clicar:

<figure><img src="../.gitbook/assets/image (450).png" alt=""><figcaption></figcaption></figure>

Após clicar:

<figure><img src="../.gitbook/assets/image (451).png" alt=""><figcaption></figcaption></figure>

#### **Passo a passo para adicionar usuários:**

1. Clique no bloco para expandi-lo.
2. Localize o usuário desejado na lista (com barra de rolagem ou campo de busca).
3. Clique no botão <img src="../.gitbook/assets/image (452).png" alt="" data-size="line"> abaixo dos nomes dos usuários.
4.  Para finalizar a ação, clique no **ícone** <img src="../.gitbook/assets/image (455).png" alt="" data-size="line"> localizado ao lado do título **“Selecionados”** na tabela de visualização.

    <figure><img src="../.gitbook/assets/image (453).png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
O usuário será oficialmente adicionado à lista de usuários com permissão, passando a ter acesso ao projeto.
{% endhint %}

#### **2. Tabela "Selecionados"**

Exibe todos os usuários que já possuem acesso ao projeto, permitindo **visualização e gerenciamento** das permissões concedidas.

<figure><img src="../.gitbook/assets/image (463).png" alt=""><figcaption></figcaption></figure>

<table><thead><tr><th width="138">Coluna</th><th>Descrição</th></tr></thead><tbody><tr><td><strong>Usuário</strong></td><td>Nome completo do usuário com permissão.</td></tr><tr><td><strong>E-Mail</strong></td><td>Endereço de e-mail do usuário.</td></tr><tr><td><strong>Login</strong></td><td>Nome de usuário utilizado para acessar o sistema.</td></tr><tr><td><strong>Último Acesso</strong></td><td>Data e hora do último login, permitindo controle da atividade.</td></tr><tr><td><strong>Prazo</strong></td><td>Data de expiração do acesso (dd/mm/aaaa), com ícone de calendário, para permissões temporárias.</td></tr><tr><td><strong>Ação (X)</strong></td><td>Botão de exclusão que permite revogar o acesso do usuário individualmente.</td></tr></tbody></table>



</details>

<details>

<summary><img src="../.gitbook/assets/image (282).png" alt="" data-size="line"> Regras</summary>

Esta tela permite ao administrador **definir regras detalhadas** para grupos e usuários em relação a um recurso ou projeto. A interface é dividida em **seções.**

<figure><img src="../.gitbook/assets/image (436).png" alt=""><figcaption></figcaption></figure>

#### 1. Bloco Expansível

<table data-card-size="large" data-view="cards"><thead><tr><th></th><th data-hidden data-card-cover data-type="image">Cover image</th></tr></thead><tbody><tr><td><p><img src="../.gitbook/assets/image (457).png" alt=""></p><ul><li><strong>Função:</strong> Adicionar um grupo inteiro de usuários às regras de permissão.</li><li><strong>Interação:</strong> Ao clicar no bloco, ele se expande mostrando a lista de grupos disponíveis.</li><li><p><strong>Como adicionar:</strong></p><ol><li>Selecione o grupo desejado.</li><li>Clique no botão azul <strong>“+”</strong> para movê-lo para a tabela <strong>“Selecionados”</strong>.</li><li>Para finalizar a ação, clique no <strong>ícone</strong> <img src="../.gitbook/assets/image (455).png" alt="" data-size="line"> localizado ao lado do título <strong>“Selecionados”</strong> na tabela de visualização.<br></li></ol></li></ul></td><td></td></tr><tr><td><div><figure><img src="../.gitbook/assets/image (459).png" alt="" width="264"><figcaption></figcaption></figure></div><ul><li><strong>Função:</strong> Adicionar usuários individuais às regras de permissão.</li></ul><ul><li><strong>Interação:</strong> Funciona de forma semelhante ao bloco de grupos, expandindo-se ao ser clicado.</li><li><p><strong>Como adicionar:</strong></p><ol><li>Localize o usuário desejado na lista.</li><li>Clique no botão azul <strong>“+”</strong> para incluí-lo na tabela <strong>“Selecionados”</strong>.</li><li>Para finalizar a ação, clique no <strong>ícone</strong> <img src="../.gitbook/assets/image (455).png" alt="" data-size="line"> localizado ao lado do título <strong>“Selecionados”</strong> na tabela de visualização.<br></li></ol></li></ul></td><td></td></tr></tbody></table>

#### **2. Tabela "Selecionados"**

Exibe todos os grupos e usuários adicionados, permitindo **visualização e configuração detalhada de permissões**.

<figure><img src="../.gitbook/assets/image (462).png" alt="" width="551"><figcaption></figcaption></figure>

<table><thead><tr><th width="161">Coluna</th><th>Descrição</th></tr></thead><tbody><tr><td><strong>Grupo/Usuário</strong></td><td>Nome do grupo ou usuário, incluindo e-mail ou identificador.</td></tr><tr><td><strong>Visualizar</strong></td><td>Checkbox que concede permissão apenas para visualizar o conteúdo.</td></tr><tr><td><strong>Editar</strong></td><td>Checkbox que concede permissão para modificar o conteúdo.</td></tr><tr><td><strong>Gerenciar</strong></td><td>Checkbox que concede permissões avançadas, como adicionar/remover usuários ou alterar configurações.</td></tr><tr><td><strong>Prazo</strong></td><td>Campo para inserir uma data de expiração do acesso.</td></tr><tr><td><strong>Ação (X)</strong></td><td>Botão para remover o usuário ou grupo da lista de permissões.</td></tr></tbody></table>



</details>

<details>

<summary><img src="../.gitbook/assets/image (283).png" alt="" data-size="line"> Editar Projeto</summary>

Esta tela permite que usuários com as devidas permissões **visualizem e editem projetos existentes**.

{% hint style="info" %}
Para aprender como cadastrar e editar um projeto, [**clique aqui**](como-cadastrar-e-editar-projetos..md).
{% endhint %}

<figure><img src="../.gitbook/assets/image (464).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><img src="../.gitbook/assets/image (287).png" alt="" data-size="line"> Excluir Projeto</summary>

Ao clicar no ícone **“X”** para excluir um projeto, o sistema **não realiza a exclusão imediata**.\
Por motivos de segurança e controle, **apenas o Administrador do sistema** possui permissão para concluir essa ação.

Assim que o usuário solicita a exclusão, o sistema exibe uma **notificação informando que um e-mail de autorização foi enviado ao Administrador**.

<figure><img src="../.gitbook/assets/image (465).png" alt=""><figcaption></figcaption></figure>

Dessa forma, a exclusão só será efetivada **após a aprovação e execução pelo Administrador**.

</details>

### Detalhes – Ações disponíveis na parte inferior:

<figure><img src="../.gitbook/assets/image (467).png" alt="" width="525"><figcaption></figcaption></figure>

<details>

<summary><mark style="color:red;">Formulários</mark></summary>

O botão **“Formulários”** direciona o usuário para a página de **Formulários de Indexação**, onde são definidos os metadados do projeto.

Nesta seção, é possível **criar, editar e gerenciar formulários** utilizados para a **indexação de documentos**, configurando os campos (metadados) que serão preenchidos durante o cadastro de objetos no sistema.

Cada formulário representa um **modelo de informações estruturadas**, que auxilia o sistema na **localização, classificação e recuperação eficiente** dos documentos, garantindo **organização e rastreabilidade** no processo de gestão.

{% hint style="info" %}
**⚙️ Indexação de Arquivos com Campos Fixos**

Agora é possível **configurar metadados fixos por projeto**, permitindo que determinados campos sejam **preenchidos diretamente na configuração do projeto**.\
Esses metadados permanecem padronizados para todos os formulários vinculados, garantindo **uniformidade e rastreabilidade** nas indexações.

Além disso, os dados configurados como fixos passam a integrar o **relatório analítico de arquivos**, ampliando a **visão gerencial** sobre o acervo e facilitando o controle das informações indexadas.
{% endhint %}

<figure><img src="../.gitbook/assets/image (468).png" alt=""><figcaption></figcaption></figure>

#### **Ações disponíveis:**

**1. Criar novo formulário** <img src="../.gitbook/assets/image (90).png" alt="" data-size="original">

Ao clicar no ícone **“Novo Formulário”** <img src="../.gitbook/assets/image (85).png" alt="" data-size="line">, localizado na parte superior da tela, o sistema abrirá automaticamente o **painel de criação** no lado direito.

Nesta etapa, todos os campos aparecerão **em branco**, prontos para serem preenchidos conforme os **parâmetros e necessidades do projeto**. Após inserir as informações desejadas, basta salvar para concluir o registro do novo formulário.

Realize a criação e clique em <img src="../.gitbook/assets/image (88).png" alt="" data-size="line"> para confirmar.

***

**2. Editar formulário existente ✏️**

Para editar um formulário já cadastrado, selecione o item desejado na **lista lateral esquerda**.

Ao clicar sobre o **título do formulário**, o sistema exibirá, no painel direito, o **formulário preenchido com os dados originais**. O título da tela será atualizado automaticamente para:

<figure><img src="../.gitbook/assets/image (86).png" alt=""><figcaption></figcaption></figure>

Realize as alterações necessárias e clique em <img src="../.gitbook/assets/image (89).png" alt="" data-size="line"> para confirmar.

{% hint style="info" %}
**Dica:** Durante a edição, será exibido um **ícone de regras (**<img src="../.gitbook/assets/image (87).png" alt="" data-size="line">**)** ao lado do título. A partir dele, é possível definir as **regras de acesso** e controle de uso do formulário, garantindo maior segurança e personalização.
{% endhint %}

</details>

<details>

<summary><mark style="color:blue;">Abrir</mark></summary>

Ao clicar em **Abrir**, o usuário é direcionado automaticamente para o módulo **Pesquisar**, onde poderá realizar a busca por objetos vinculados ao projeto selecionado.

{% hint style="info" %}
Para aprender como efetuar buscas por objetos no sistema, [**clique aqui**](../pesquisar/como-pesquisar-objetos/)
{% endhint %}

</details>



### 📌 **Mais possibilidades:**

<table data-card-size="large" data-view="cards"><thead><tr><th align="center"></th><th data-hidden data-card-target data-type="content-ref"></th></tr></thead><tbody><tr><td align="center"><strong>Como criar um projeto?</strong></td><td><a href="como-cadastrar-e-editar-projetos..md#como-criar-um-novo-projeto">#como-criar-um-novo-projeto</a></td></tr><tr><td align="center"><strong>Como editar projetos no DocZ?</strong></td><td><a href="como-cadastrar-e-editar-projetos..md#como-editar-um-projeto">#como-editar-um-projeto</a></td></tr></tbody></table>



<a href="../painel.md" class="button secondary" data-icon="circle-left">Retornar para anterior</a>
