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
---

# Emitir ficha de transporte

A funcionalidade **Ficha de Transporte de Documentos** permite formalizar e registrar a movimentação de caixas e documentos entre locais de origem e destino.

Além de servir como comprovante da transferência documental, a ficha reúne informações sobre o acervo transportado, responsáveis envolvidos e dados logísticos da movimentação.

{% hint style="info" %}
**Permissão necessária**

Para acessar esta funcionalidade, o usuário deve possuir a permissão:

**Emitir Ficha de Transporte de Documentos**
{% endhint %}

<figure><img src="../../.gitbook/assets/image (568).png" alt=""><figcaption></figcaption></figure>

#### Como acessar

1. Acesse o menu **Solicitações**.
2. Clique em **Ficha de Transporte**.

O sistema exibirá a tela de gerenciamento das fichas cadastradas.

#### Ações disponivéis:

<details>

<summary>Emitindo uma nova Ficha de Transporte</summary>

<figure><img src="../../.gitbook/assets/image (571).png" alt=""><figcaption></figcaption></figure>

Para criar uma nova ficha:

1. Na tela de Fichas de Transporte, clique em **Nova Ficha de Transporte**.
2. Preencha os campos solicitados.
3. Clique em **Gerar Ficha de Transporte**.

O sistema criará automaticamente um número de identificação para a ficha e registrará a emissão no sistema.

</details>

<details>

<summary> <img src="../../.gitbook/assets/image (572).png" alt="" data-size="line"> Informações da Ficha</summary>

Para acessar a ficha de transporte, clique no ícone ![](<../../.gitbook/assets/image (570).png>) da coluna "Ações".

<figure><img src="../../.gitbook/assets/image (569).png" alt=""><figcaption></figcaption></figure>

Durante o cadastro, podem ser informados os seguintes dados:

* Ordem de Serviço vinculada (opcional);
* Contratante;
* Contratada;
* Acervo;
* Endereço de origem;
* Endereço de destino;
* Descrição do conteúdo transportado;
* Data-limite;
* Quantidade de caixas;
* Observações;
* Responsável pelo acervo;
* Responsável da contratada;
* Responsável da instituição destinatária;
* Data da emissão.

</details>

<details>

<summary> <img src="../../.gitbook/assets/image (573).png" alt="" data-size="line"> Download da Ficha</summary>

Para isso:

1. Localize a ficha desejada na lista.
2. Clique no ícone **Baixar PDF**.

O documento será gerado conforme o modelo de Ficha de Transporte configurado no sistema.

</details>

<details>

<summary><img src="../../.gitbook/assets/image (574).png" alt=""> Upload da Ficha Assinada</summary>

Após a impressão e assinatura da ficha, é possível anexar a versão assinada ao cadastro.

<figure><img src="../../.gitbook/assets/image (575).png" alt=""><figcaption></figcaption></figure>

**Como realizar o upload**

1. Localize a ficha na lista.
2. Clique no ícone **Upload de Ficha de Transporte**.
3. Selecione o arquivo assinado.
4. Clique em **Enviar**.

Formatos aceitos:

* PDF
* JPG
* PNG
* TIFF

Após o envio, o status da ficha será atualizado automaticamente para **Assinada**.

</details>

<details>

<summary><img src="../../.gitbook/assets/image (576).png" alt="" data-size="original"> Cancelar uma Ficha de Transporte</summary>

Caso a movimentação não seja realizada, a ficha poderá ser cancelada.

<figure><img src="../../.gitbook/assets/image (577).png" alt=""><figcaption></figcaption></figure>

1. Localize a ficha desejada.
2. Clique no ícone **Cancelar Ficha**.
3. Confirme a operação.

Após a confirmação, o status da ficha será alterado para **Cancelada**.

</details>

<details>

<summary>Status da Ficha</summary>

Durante seu ciclo de vida, a ficha pode assumir os seguintes status:

| Status    | Descrição                            |
| --------- | ------------------------------------ |
| Emitida   | Ficha criada e registrada no sistema |
| Assinada  | Ficha assinada e anexada ao cadastro |
| Cancelada | Ficha cancelada pelo usuário         |

_O status "Enviada" existe para integrações específicas e pode não estar disponível em todos os ambientes._

</details>

<details>

<summary>Vinculando uma Ficha de Transporte à Ordem de Serviço</summary>

Após a emissão da Ficha de Transporte, é possível vinculá-la a uma Ordem de Serviço para manter o histórico e a rastreabilidade da movimentação documental.

**Como vincular uma Ficha de Transporte à O.S.**

1. Acesse o menu **Solicitações**.
2. Clique em **Todas as Solicitações**.
3. Localize a Ordem de Serviço desejada.
4. Clique em **Andamento O.S.**.
5. Selecione a opção **Nova Ocorrência**.
6. No campo **Tipo de Ocorrência**, escolha a opção **Vincular Ficha de Transporte**.
7. Selecione o número da Ficha de Transporte que deseja associar à O.S.
8. Clique em **Confirmar**.

Após a confirmação, a Ficha de Transporte ficará vinculada à Ordem de Serviço e poderá ser consultada posteriormente por meio do histórico de ocorrências da O.S., facilitando o acompanhamento das movimentações relacionadas ao transporte documental.

</details>

<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
