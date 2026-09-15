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
  anchors:
    visible: true
---

# App DocZ

O **DocZ Mobile** é o aplicativo utilizado para executar operações de gestão documental diretamente no campo ou no ambiente de armazenamento físico.

Ele permite que usuários realizem atividades como:

* consulta de documentos e caixas
* leitura de códigos de barras ou QR Codes
* movimentação de objetos
* criação de solicitações
* registro de localização
* acompanhamento de histórico e status documental

O aplicativo possui **interface otimizada para dispositivos móveis**, permitindo que as operações sejam realizadas por smartphones ou tablets durante atividades operacionais no acervo.

<figure><img src="../.gitbook/assets/unknown.png" alt="" width="563"><figcaption></figcaption></figure>

### Ações e funcionalidades no aplicativo DocZ:

<details>

<summary><strong>Acesso ao Aplicativo</strong></summary>

O acesso ao aplicativo ocorre por meio da **tela de autenticação**, onde o usuário deve informar suas credenciais para iniciar a sessão no sistema.

{% hint style="warning" %}
**Importante:**\
As credenciais utilizadas no aplicativo são **as mesmas da aplicação web do DocZ**. Portanto, **não é necessário criar um novo usuário ou senha para utilizar o aplicativo**.
{% endhint %}

#### Fluxo de acesso

1. O usuário informa **Usuário, Senha e Cliente**.
2. O sistema realiza a validação das credenciais informadas.
3. Caso os dados estejam corretos, o sistema direciona o usuário para a **tela de seleção de projetos disponíveis**.
4. Caso haja erro na autenticação, o sistema exibe uma **mensagem de alerta** e permanece na tela de login para que o usuário realize uma nova tentativa.

</details>

<details>

<summary><strong>Seleção de Projeto</strong></summary>

Após o login, o usuário visualiza os **projetos disponíveis para seu perfil de acesso**.

A lista apresentada é definida com base em dois critérios:

* **Cliente informado no login**
* **Perfil de acesso do usuário**

Esse mecanismo garante o **isolamento de dados entre clientes (multi-tenant)** e restringe o acesso apenas aos projetos autorizados.&#x20;

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Após selecionar o projeto, o usuário é direcionado para o **Menu Principal do aplicativo**.

</details>

### **Menu Lateral de Navegação**

O **Menu Principal** concentra as principais funcionalidades operacionais do aplicativo.

O menu lateral permite acesso rápido às funcionalidades completas do sistema.

_Ao selecionar uma opção, o sistema carrega automaticamente a tela correspondente._

<figure><img src="../.gitbook/assets/image (651).png" alt=""><figcaption></figcaption></figure>

<details>

<summary><strong>Arquivar Caixa</strong></summary>

Essa funcionalidade permite **associar caixas ou objetos a um container**, como caixas, paletes ou lotes, garantindo a rastreabilidade do arquivamento.

**Fluxo de arquivamento**

1. Informar o **container principal** (unidade de destino).
2. Informar o(s) **objeto(s)** que serão armazenados no container.
3. Confirmar novamente o **container principal** para finalizar a operação.

Os itens processados são exibidos em uma **tabela de conferência**, indicando o objeto e sua localização.

O sistema exibe o **total de itens processados**, permitindo que o usuário acompanhe o arquivamento e evite erros de conferência.

</details>

<details>

<summary><strong>Importar Legado</strong></summary>

<figure><img src="../.gitbook/assets/image (671).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><strong>Arquivar documento</strong></summary>

Essa funcionalidade permite **associar documentos ou objetos a um container**, como caixas, paletes ou lotes, garantindo a rastreabilidade do arquivamento.

**Fluxo de arquivamento**

1. Informar o **container principal** (unidade de destino).
2. Informar o(s) **objeto(s)** que serão armazenados no container.
3. Confirmar novamente o **container principal** para finalizar a operação.

Os itens processados são exibidos em uma **tabela de conferência**, indicando o objeto e sua localização.

O sistema exibe o **total de itens processados**, permitindo que o usuário acompanhe o arquivamento e evite erros de conferência.

</details>

<details>

<summary><strong>Auditoria de O.S</strong></summary>

<figure><img src="../.gitbook/assets/image (671).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><mark style="color:$tint;"><strong>Fotolabel do Espelho da Caixa</strong></mark></summary>

A funcionalidade **Fotolabel do Espelho da Caixa** permite fotografar os espelhos das caixas de um pallet de forma sequencial e enviar as imagens ao DocZ ao final da operação.

<figure><img src="../.gitbook/assets/image (658).png" alt="" width="375"><figcaption></figcaption></figure>

### Como utilizar

1. Acesse **Fotolabel do Espelho da Caixa** no aplicativo.
2. Selecione **Leitor** para realizar a leitura das etiquetas. A leitura pode ser feita pelo aparelho ou pela câmera do celular/tablet, conforme a operação.
3. Faça a leitura da **etiqueta do pallet**, que identifica as caixas vinculadas a ele.\
   ![](<../.gitbook/assets/image (659).png>)
4. Faça a leitura da **primeira caixa**. A câmera do dispositivo será aberta automaticamente.\
   ![](<../.gitbook/assets/image (660).png>)
5. **Fotografe o espelho da caixa**.\
   ![](<../.gitbook/assets/image (661).png>)
6. Repita a leitura e a fotografia para cada caixa do pallet.\
   ![](<../.gitbook/assets/image (662).png>)
7. Após concluir todas as caixas, selecione **Enviar** para encaminhar as imagens ao DocZ.\
   ![](<../.gitbook/assets/image (663).png>)

> **Importante:** realize o procedimento para todas as caixas do pallet antes de selecionar **Enviar**.

</details>

<details>

<summary><mark style="color:$tint;"><strong>Fotolabel com Indexação Automática</strong></mark></summary>

A funcionalidade **Fotolabel com Indexação Automática** permite registrar o espelho da caixa pelo aplicativo DocZ e encaminhá-lo automaticamente para processamento e indexação.

### Como acessar

No aplicativo DocZ, acesse o **menu principal** e selecione:

<mark style="background-color:blue;">**Fotolabel com Indexação Automática**</mark>

### Como utilizar:

Após acessar a funcionalidade, siga as etapas apresentadas pelo aplicativo:

<figure><img src="../.gitbook/assets/image (664).png" alt="" width="375"><figcaption></figcaption></figure>

**1. Informe a localização**\
Selecione a localização correspondente à caixa.

**2. Identifique a caixa**\
Informe ou realize a leitura das informações necessárias para identificar a caixa que será processada.

**3. Fotografe o espelho da caixa**\
Tire uma foto do espelho da caixa utilizando o aplicativo.

**4. Envie a imagem**\
Após a conclusão do fluxo, o aplicativo realiza o upload da imagem para o DocZ.

<div align="left"><figure><img src="../.gitbook/assets/image (668).png" alt="" width="375"><figcaption></figcaption></figure></div>

#### O que acontece depois?

Após a identificação da caixa e conclusão do fluxo, o DocZ altera automaticamente o **Status da Gestão Documental** para:

> **DISPONÍVEL PARA DOCFY**

<figure><img src="../.gitbook/assets/image (652).png" alt=""><figcaption></figcaption></figure>

Em seguida, o espelho da caixa é encaminhado automaticamente para processamento pelo **Docfy**.

#### Resumindo

**Localização → Caixa → Foto do espelho → Status atualizado → Processamento → Indexação**

Essa sequência reduz etapas manuais e permite que as informações do espelho sejam processadas para facilitar a identificação e consulta da caixa.

{% hint style="info" %}
#### **💡 Atenção**

Caso a opção **Fotolabel com Indexação Automática** não esteja disponível ou seja apresentada uma mensagem informando que o status **DISPONÍVEL PARA DOCFY** não está configurado, entre em contato com o **Suporte SOSDOCS**.
{% endhint %}

</details>

<details>

<summary><mark style="color:$tint;"><strong>Consultar Objeto</strong></mark></summary>

A funcionalidade **Consulta de Objeto** permite localizar caixas ou documentos dentro do projeto ativo.

Por meio dessa funcionalidade, o usuário pode acessar informações detalhadas do objeto, visualizar seu histórico de movimentações e realizar determinadas ações operacionais.

#### **Métodos de consulta**

O sistema permite três formas de entrada de dados:

<table data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><strong>Scan:</strong> Captura do código do objeto utilizando a câmera do dispositivo.</td></tr><tr><td><strong>Leitor:</strong> Leitura do código por meio de scanner ou leitor externo.</td></tr><tr><td><strong>Texto:</strong> Digitação manual do código identificador do objeto.</td></tr></tbody></table>

Após a leitura ou digitação, o sistema processa a consulta e apresenta as informações do objeto localizado.

#### **Visualização de Detalhes do Objeto**

Após a realização da consulta, o sistema apresenta a tela de **detalhes do objeto**, contendo as principais informações cadastradas no sistema.

<figure><img src="../.gitbook/assets/image (653).png" alt="" width="250"><figcaption></figcaption></figure>

A partir dessa tela, o usuário também pode acessar funcionalidades adicionais relacionadas ao objeto consultado.

**Fluxo da tela:**

Consulta de Objeto ➡️ Visualização do objeto ➡️ Histórico / Expurgo / Nova consulta

#### **↘️ Ações disponíveis:**

{% hint style="info" %}
**Consulta Contínua:** O usuário pode realizar uma nova busca de objeto diretamente pelos botões superiores sem precisar sair da tela de histórico.
{% endhint %}

<table data-card-size="large" data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><img src="../.gitbook/assets/image (655).png" alt=""></p><p><strong>Histórico do Objeto</strong></p><p>A funcionalidade <strong>Histórico do Objeto</strong> apresenta o registro completo das movimentações e alterações realizadas no item ao longo do tempo.</p><p>Cada registro do histórico contém:</p><ul><li><strong>Data e hora</strong> da ocorrência</li><li><strong>Tipo de evento</strong> registrado</li><li><strong>Usuário ou sistema responsável pela ação</strong></li></ul><p>Esse recurso permite acompanhar o <strong>ciclo de vida documental do objeto.</strong></p></td></tr><tr><td><p><img src="../.gitbook/assets/image (656).png" alt=""></p><p><strong>Expurgo do Objeto</strong></p><p>O <strong>expurgo</strong> representa o descarte definitivo do objeto no sistema, indicando que o item atingiu o fim de seu ciclo de vida documental.</p><p><strong>Ações disponíveis:</strong></p><ul><li><strong>Cancelar:</strong> fecha a janela e retorna à consulta do objeto sem alterações.</li><li><strong>Confirmação de Sucesso: a</strong>pós a confirmação, o sistema exibe a mensagem <strong>“Expurgo solicitado com sucesso”</strong>.</li></ul><p>A operação é registrada no <strong>histórico do objeto.</strong></p></td></tr></tbody></table>



</details>

<details>

<summary><mark style="color:$tint;"><strong>Consultar Conteúdo</strong></mark></summary>

Essa funcionalidade permite visualizar todos os **documentos ou objetos armazenados em um container específico**.

Após informar o código do container, o sistema apresenta a listagem de itens vinculados à unidade de armazenamento.

**Métodos de consulta**

O sistema permite três formas de entrada de dados:

<table data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><strong>Scan:</strong> Captura do código do objeto utilizando a câmera do dispositivo.</td></tr><tr><td><strong>Leitor:</strong> Leitura do código por meio de scanner ou leitor externo.</td></tr><tr><td><strong>Texto:</strong> Digitação manual do código identificador do objeto.</td></tr></tbody></table>

Após a consulta, o sistema apresenta a **lista de objetos vinculados ao container**.

Cada item pode ser selecionado para **visualização detalhada**.

<figure><img src="../.gitbook/assets/image (669).png" alt=""><figcaption></figcaption></figure>

**Detalhes do Objeto**

Ao selecionar um item da lista e clicar em ![](<../.gitbook/assets/image (670).png>) , o sistema exibe um **modal com as informações completas do objeto**.

Entre os dados apresentados estão:

<table data-header-hidden><thead><tr><th width="88"></th><th></th><th width="135"></th><th width="77"></th><th width="117"></th><th></th></tr></thead><tbody><tr><td>Assunto</td><td>Classificação</td><td>Departamento</td><td>ID SOS</td><td>Localização</td><td>Status do documento</td></tr></tbody></table>

<img src="https://manualsosdocs.gitbook.io/docz-operacao/~gitbook/image?url=https%3A%2F%2F4238095802-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FjN82lf9J2JvpduBsGL1I%252Fuploads%252FQugfcEBXlXlJWTXfrct3%252Funknown.png%3Falt%3Dmedia%26token%3D3df3c29d-c1c1-4b67-9fab-4eda151463c7&#x26;width=768&#x26;dpr=3&#x26;quality=100&#x26;sign=82f2f7ebd8bcf44fa921a7c9b382473d&#x26;sv=3" alt="" width="375">

Essas informações permitem a **conferência detalhada do registro e sua rastreabilidade no sistema**.

</details>



<a href="../" class="button secondary" data-icon="circle-left">Voltar</a>
