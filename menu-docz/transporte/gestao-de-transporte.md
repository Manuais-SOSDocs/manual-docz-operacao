---
description: MENU > TRANSPORTE > GESTÃO DE TRANSPORTE
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

# Gestão de transporte

Esta aba permite registrar e organizar o transporte de Ordens de Serviço (O.S.) com controle de equipe, veículo e itens.

<details>

<summary><strong>🛻 Como Criar um Novo Transporte</strong></summary>

{% stepper %}
{% step %}
Clique em <img src="../../.gitbook/assets/image (13).png" alt="" data-size="line">\
Localizado no canto inferior direito da grid de transportes.

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Preencha os dados básicos na pop-up que se abrirá

{% hint style="info" %}
**🚚 Seleção de Responsáveis pelo Transporte (Motorista/Ajudante):** O campo de seleção agora exibe apenas os colaboradores cadastrados no CRUD “Responsáveis pelo Transporte”, conforme função (Motorista/Ajudante).
{% endhint %}

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Clique no botão <img src="../../.gitbook/assets/image (16).png" alt="" data-size="line"> para prosseguir.

Você será redirecionado para a tela de detalhamento do transporte.
{% endstep %}

{% step %}
Detalhe as especificações sobre o transporte.

<figure><img src="../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Se houver, selecione no campo “Ajudante”.
{% endstep %}

{% step %}
Escolha as ordens de serviço que farão parte do transporte.

**Clique em** <img src="../../.gitbook/assets/image (18).png" alt="" data-size="line"> para adicionar as O.S. aos **Itens do Transporte**.
{% endstep %}

{% step %}
Para finalizar, clique em <img src="../../.gitbook/assets/image (19).png" alt="" data-size="line">
{% endstep %}
{% endstepper %}

{% hint style="success" %}
**Transporte criado com sucesso.**
{% endhint %}

</details>

<details>

<summary><strong>📦 Acompanhamento e Atendimento de Transportes – Passo a Passo</strong></summary>

{% stepper %}
{% step %}
Volte para a tela inicial de Transportes
{% endstep %}

{% step %}
Visualize as solicitações\
Será exibida a lista de todos os transportes em aberto.

<figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Clique no ícone da lupa 🔍\
Isso abrirá a tela detalhada do transporte selecionado.

<figure><img src="../../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Clique em <img src="../../.gitbook/assets/image (22).png" alt="" data-size="line">
{% endstep %}

{% step %}
Na coluna dos itens adicionados ao transporte, poderá atualizar o status da entrega:

* ❌ Excluir – Remove o item da lista.
* ✅ Atender – Registra que o transporte iniciou a rota de entrega.
* 📍 Cheguei – Informa que o entregador chegou ao destino.
* 🕒 Atrasado – Registra atraso no atendimento.
* 🚫 Cancelar – Cancela o item da rota de transporte.
{% endstep %}

{% step %}
Caso seja necessário, na parte inferior da tela, há um **campo para Observações**, onde é possível registrar informações adicionais ou ocorrências durante o transporte.
{% endstep %}

{% step %}
Ao finalizar o transporte clique em ![](<../../.gitbook/assets/image (23).png>)
{% endstep %}
{% endstepper %}

{% hint style="success" %}
**Ação concluída com sucesso!**
{% endhint %}

</details>

<details>

<summary><strong>📋 Rastreabilidade e Histórico da Ordem de Serviço</strong></summary>

Para ampliar a visibilidade do processo logístico, o DocZ registra automaticamente no histórico da Ordem de Serviço (O.S.) as principais movimentações realizadas durante a execução de um transporte vinculado.

Dessa forma, o usuário pode acompanhar o andamento da operação diretamente pela O.S., sem necessidade de acessar o módulo de Gestão de Transporte.

**Ocorrências registradas automaticamente**

As seguintes ações realizadas no transporte geram registros automáticos no histórico da Ordem de Serviço:

| Ação no Transporte | Ocorrência registrada na O.S. |
| ------------------ | ----------------------------- |
| Atender            | Transporte Iniciado           |
| Atrasado           | Transporte Atrasado           |
| Cheguei            | Transporte no Local           |
| Finalizar          | Transporte Finalizado         |
| Cancelar           | Transporte Cancelado          |

**Informações registradas**

Cada ocorrência registrada no histórico da O.S. contém:

* Usuário responsável pela ação;
* Data e hora da ocorrência;
* Descrição da ocorrência;
* Observações registradas durante a operação;
* Referência ao transporte vinculado.

**Referência ao transporte**

A coluna **Observação** exibe automaticamente o transporte que originou a movimentação.

Exemplos:

**Com observação preenchida:**

> Coleta realizada com sucesso | Transporte 000123/2026

**Sem observação preenchida:**

> Transporte 000123/2026

O número do transporte é exibido como um link clicável, permitindo acesso direto ao registro correspondente.

**Importante**

* Apenas a Ordem de Serviço vinculada ao item movimentado recebe o registro da ocorrência.
* O histórico da O.S. mantém a rastreabilidade completa das ações realizadas durante o transporte.
* Os registros são criados automaticamente e não exigem intervenção do usuário.

</details>

<details>

<summary><strong>🔖 Ocorrências do Transporte</strong></summary>

As ocorrências permitem registrar e acompanhar os eventos que acontecem durante a execução do transporte, fornecendo maior controle operacional e rastreabilidade das atividades realizadas.

Durante o ciclo de vida do transporte, o usuário poderá registrar diferentes tipos de ocorrências para cada item vinculado.

As principais ocorrências disponíveis são:

<table><thead><tr><th width="128.66668701171875">Ocorrência</th><th>Descrição</th></tr></thead><tbody><tr><td>Atender</td><td>Indica o início do atendimento do item transportado.</td></tr><tr><td>Atrasado</td><td>Informa que houve atraso na execução da atividade prevista.</td></tr><tr><td>Cheguei</td><td>Registra a chegada ao local de coleta ou entrega.</td></tr><tr><td>Finalizar</td><td>Conclui o atendimento do item transportado.</td></tr><tr><td>Cancelar</td><td>Cancela a operação relacionada ao item selecionado.</td></tr></tbody></table>

Cada ocorrência registra automaticamente informações como:

* Usuário responsável pela ação;
* Data e hora da movimentação;
* Tipo da ocorrência executada;
* Observações informadas pelo usuário.

As ocorrências ficam disponíveis para consulta durante todo o ciclo do transporte, permitindo acompanhar o andamento das atividades e identificar rapidamente eventos relevantes ocorridos durante a operação.

{% hint style="info" %}
Importante:

As movimentações realizadas nos itens do transporte também podem ser registradas automaticamente no histórico da Ordem de Serviço vinculada, ampliando a rastreabilidade do processo logístico.
{% endhint %}

</details>



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
