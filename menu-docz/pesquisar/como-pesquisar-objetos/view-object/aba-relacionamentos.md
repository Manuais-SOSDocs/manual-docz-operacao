# Aba - Relacionamentos

{% hint style="info" %}
O acesso a esta aba depende do **perfil de permissões do usuário**. Em caso de dúvidas, entre em contato com o suporte técnico ou com o gerente de projetos responsável do Grupo SOS Docs.
{% endhint %}

A aba **Relacionamentos** permite criar vínculos entre documentos relacionados, facilitando a organização, rastreabilidade e controle das informações armazenadas no sistema.

Por meio dessa funcionalidade, é possível identificar documentos que possuem relação entre si, como anexos, apensos ou outros tipos de vínculo definidos pela organização.

<figure><img src="https://manualsosdocs.gitbook.io/~gitbook/image?url=https%3A%2F%2F4270511437-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FTOkpktW1KcGIR73wpKDq%252Fuploads%252FFIjCzhma0gTTeEqrP4tJ%252Fimage.png%3Falt%3Dmedia%26token%3D78e460aa-5f8b-4716-9c37-0a9ef94e0513&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=b120be98&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### Informações exibidas

A grade apresenta informações como:

* Documento Principal;
* Identificador SOS;
* Localização;
* Status;
* Tipo de Objeto;
* Identificador Cliente;
* Número Concorrente;
* Data do Relacionamento;
* Tipo de Relacionamento;
* Justificativa.

Um documento pode possuir múltiplos relacionamentos ativos simultaneamente.

#### **Ações e eventos disponíveis:**

<details>

<summary>Requisitos de acesso</summary>

A funcionalidade estará disponível somente quando:

* O parâmetro **Permitir Relacionamentos** estiver habilitado no projeto;
* O usuário possuir permissão de **Visualização** e **Edição** na pasta do documento;
* O usuário possuir acesso à View Object.

</details>

<details>

<summary>Criando um relacionamento</summary>

Para criar um relacionamento:

1. Acesse a aba **Relacionamentos**.
2. Clique em **Criar Relacionamento**.
3. Localize o documento desejado utilizando um dos filtros disponíveis:
   * Identificador SOS;
   * Identificador Cliente;
   * Número Concorrente;
   * Descrição.
4. Clique em **Relacionar**.
5. Informe:
   * Tipo de Relacionamento;
   * Justificativa.
6. Confirme a operação.

Após a confirmação, o vínculo será criado e passará a ser exibido na grade de relacionamentos.

</details>

<details>

<summary>Acessando documentos relacionados</summary>

Quando o usuário possuir permissão de acesso ao documento relacionado, o campo **Identificador SOS** será exibido como link, permitindo abrir diretamente o documento vinculado.

</details>

<details>

<summary>Desfazendo relacionamentos</summary>

Usuários com a permissão **Desfazer Relacionamentos** podem remover vínculos existentes.

Antes da remoção, o sistema solicitará confirmação da operação.

</details>

<details>

<summary>Arquivos relacionados</summary>

Quando existirem documentos relacionados com arquivos digitais vinculados, eles poderão ser visualizados na aba **Arquivos**, respeitando as permissões de acesso do usuário.

Os arquivos relacionados são identificados visualmente para facilitar sua localização.

</details>

<details>

<summary>Bloqueio de destinação documental</summary>

Documentos que possuam relacionamentos ativos não podem ser destinados individualmente.

Ao tentar executar uma destinação documental, o sistema verifica a existência de vínculos ativos e poderá bloquear a operação.

Para prosseguir, é necessário:

* Remover o relacionamento existente; ou
* Incluir todos os documentos relacionados na mesma Ordem de Serviço.

Essa validação evita a eliminação, recolhimento ou destinação parcial de documentos que possuem dependência documental.

</details>

<details>

<summary>Auditoria e rastreabilidade</summary>

Todas as operações realizadas na funcionalidade são registradas automaticamente na Trilha de Auditoria, incluindo:

* Criação de relacionamentos;
* Desfazimento de relacionamentos;
* Tentativas de destinação bloqueadas;
* Destinações realizadas com todos os documentos relacionados incluídos na mesma Ordem de Serviço.

Esses registros garantem rastreabilidade completa das ações executadas no sistema.

</details>

<details>

<summary>Destinação de Documentos Relacionados</summary>

#### Destinação de Documentos Relacionados

Antes de concluir uma solicitação de destinação documental, o sistema verifica automaticamente se os documentos selecionados possuem relacionamentos ativos com outros documentos.

Essa validação é aplicada tanto para processos de:

* Eliminação (Expurgo);
* Guarda Permanente (Recolhimento).

**Como funciona a validação**

Ao clicar em **Enviar Solicitação**, o sistema analisa todos os documentos presentes no carrinho de solicitação.

Se não existirem relacionamentos ativos, a solicitação é criada normalmente.

Caso sejam identificados documentos relacionados que não estejam incluídos na mesma solicitação, o sistema interrompe a operação e exibe uma janela de validação contendo:

* Documento selecionado;
* Documento relacionado;
* Tipo de relacionamento.

**Opções disponíveis**

Quando houver relacionamentos pendentes, o usuário poderá escolher uma das seguintes ações:

<table data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><strong>Gerenciar Relacionamentos</strong></p><p>Redireciona para a aba <strong>Relacionamentos</strong> do documento, permitindo consultar ou remover vínculos existentes, desde que o usuário possua a permissão necessária.</p></td></tr><tr><td><p><strong>Incluir Documentos Relacionados</strong></p><p>Inclui automaticamente na solicitação todos os documentos vinculados aos documentos originalmente selecionados.</p><p>Documentos já presentes no carrinho não serão adicionados novamente.</p></td></tr><tr><td><p><strong>Cancelar</strong></p><p>Cancela a operação e fecha a janela de validação.</p></td></tr></tbody></table>

**Quando a destinação será permitida**

A solicitação somente poderá ser concluída quando:

* Não existirem relacionamentos ativos; ou
* Todos os documentos relacionados estiverem incluídos na mesma solicitação; ou
* Os relacionamentos tiverem sido removidos por usuário autorizado.

**Permissão para desfazer relacionamentos**

A remoção de vínculos documentais é permitida apenas para usuários que possuam a permissão **Desfazer Relacionamentos**.

Nesses casos, a ação estará disponível na aba **Relacionamentos** e exigirá confirmação antes da exclusão do vínculo.

**Auditoria e rastreabilidade**

O sistema registra automaticamente as seguintes operações na Trilha de Auditoria:

* Visualização de relacionamentos;
* Remoção de relacionamentos;
* Inclusão automática de documentos relacionados;
* Cancelamento da operação;
* Tentativas de destinação bloqueadas.

Esses registros garantem a rastreabilidade completa das decisões tomadas durante o processo de destinação documental.

</details>

<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
