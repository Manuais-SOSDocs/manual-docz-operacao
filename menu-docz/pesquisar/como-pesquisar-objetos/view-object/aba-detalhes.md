# Aba - Detalhes

A aba **Detalhes** permite consultar os metadados associados ao objeto. Essas informações podem ter sido preenchidas manualmente durante a indexação ou obtidas automaticamente por meio da leitura de documentos utilizando tecnologias de reconhecimento de caracteres (OCR).

Além da consulta, esta aba também possibilita a edição dos metadados, desde que o usuário possua as permissões necessárias para realizar atividades de indexação.

Usuários sem permissão de indexação poderão apenas visualizar as informações registradas, não sendo permitido alterar os metadados do objeto.

<figure><img src="https://manualsosdocs.gitbook.io/~gitbook/image?url=https%3A%2F%2F4270511437-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FTOkpktW1KcGIR73wpKDq%252Fuploads%252F2Rt1VBoaIPw1ABCP4Sl5%252Fimage.png%3Falt%3Dmedia%26token%3D8d6c8585-c26e-4bc5-8771-f14b0a3f95df&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=3aad3ffe&#x26;sv=2" alt=""><figcaption></figcaption></figure>

#### Como funciona?

1️⃣ Realize uma pesquisa e selecione o documento desejado.

2️⃣ Clique no ícone **“Abrir”** ao lado do documento para visualizar os detalhes.

O sistema exibirá uma **tela pop-up** na aba **Detalhes**, onde é possível consultar os **metadados** atribuídos ao objeto, seja manualmente ou por leitura do fotolabel (OCR).

Nesta aba, no **canto superior esquerdo**, estão disponíveis as seguintes ações:

<figure><img src="../../../../.gitbook/assets/image (547).png" alt=""><figcaption></figcaption></figure>

<details>

<summary><strong>Editar metadados</strong></summary>

clique no ícone de disquete para salvar alterações realizadas nos metadados do documento.

_<mark style="color:$warning;">Esta ação estará disponível apenas para usuários com permissão de indexador e indexar arquivos.</mark>_

<figure><img src="../../../../.gitbook/assets/image (548).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><strong>Imprimir etiqueta</strong></summary>

clique no ícone de impressora para gerar e imprimir a etiqueta de identificação do documento, contendo informações utilizadas para controle, localização e rastreabilidade no sistema.

<figure><img src="../../../../.gitbook/assets/image (549).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary><strong>Controle de Volumes</strong></summary>

A funcionalidade **Controle de Volumes** permite criar volumes vinculados a documentos, dossiês ou processos que ainda não estejam encerrados, mantendo a continuidade do registro documental e preservando o histórico dos volumes já criados.

O recurso é utilizado quando há necessidade de iniciar um novo volume para um mesmo documento, mantendo o vínculo entre todos os volumes relacionados.

**Como funciona?**

Ao acessar a **View Object**, usuários com a permissão **Indexador** podem utilizar o botão **Criar Volume**, disponível ao lado da opção **Imprimir Etiqueta**.

<figure><img src="../../../../.gitbook/assets/image (550).png" alt=""><figcaption></figcaption></figure>

Ao criar um volume, o sistema:

* Gera automaticamente um novo Documento de Conteúdo (DC Virtual);
* Copia os metadados do documento de origem;
* Mantém o vínculo entre o documento original e o novo volume;
* Registra o relacionamento na aba **Relações**;
* Direciona automaticamente o usuário para a View Object do volume criado.

**Herança de Metadados**

O volume criado herda automaticamente as principais informações do documento de origem, incluindo:

* Classificação documental;
* Fase corrente;
* Fase intermediária;
* Destinação final;
* Metadados indexados;
* Identificador do cliente;
* Tipo de objeto.

**Criação de Novos Volumes**

Cada documento pode possuir apenas **um volume ativo por vez**.

Caso já exista um volume ativo vinculado ao documento, o sistema exibirá uma mensagem informativa indicando que o volume atual será encerrado automaticamente para permitir a criação de um novo volume.

Ao confirmar a operação:

* O volume anterior é encerrado;
* O histórico do relacionamento é preservado;
* Um novo volume é criado automaticamente;
* A numeração sequencial dos volumes é mantida.

Exemplo:

* Volume 1 → Encerrado
* Volume 2 → Ativo
* Volume 3 → Ativo após encerramento do Volume 2

**Rastreabilidade**

Todas as operações de criação de volumes são registradas automaticamente na Trilha de Auditoria do sistema, permitindo identificar:

* Usuário responsável pela ação;
* Data e hora da criação;
* Documento de origem;
* Volume criado.

{% hint style="info" %}
**Importante**

A funcionalidade estará disponível apenas quando:

* O parâmetro **Habilitar Controle de Volume** estiver ativo no projeto;
* Um campo de controle de volume estiver configurado;
* O usuário possuir a permissão **Indexador**.
{% endhint %}

O botão **Criar Volume** não será exibido para usuários sem a permissão necessária ou para objetos que não suportem controle de volumes.

</details>

<details>

<summary><strong>Ficha de metadados do objeto</strong></summary>

Os [campos de metadados](../../campos.md) podem ser personalizados conforme as especificicações do projeto. Contudo, existem campos fixos, que incluem:

* **Identificador SOS**
* **Localização**
* **Status**
* **Departamento**
* **Descrição**
* **Tipo de Objeto**
* **Ano** (novo campo adicionado, útil para documentos que não possuem data completa)
* **Etapa de Indexação**
* **Classificação**
* **Fase Corrente**
* **Fase Intermediária**
* **Destinação Final**
* **Sigilo Associado**
* **Observações**

</details>



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
