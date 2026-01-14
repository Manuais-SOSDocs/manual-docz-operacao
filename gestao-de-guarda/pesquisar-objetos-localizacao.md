---
description: MENU > GESTÃO DE GUARDA > TIPOS DE OBJETO> PESQUISAR OBJETOS LOCALIZAÇÃO
---

# Pesquisar Objetos Localização

Esta funcionalidade permite **pesquisar objetos (caixas)** a partir de diferentes tipos de endereços físicos ou operacionais, exibindo todos os objetos vinculados ao endereço informado, **independentemente do cliente**.

{% hint style="success" %}
Com as melhorias recentes, a pesquisa passou a aceitar **novos tipos de endereçamento**, além do endereço arquivístico tradicional.
{% endhint %}

<figure><img src="../.gitbook/assets/image (268).png" alt=""><figcaption></figcaption></figure>

### 📍 Tipos de endereços aceitos na pesquisa

No campo **Pesquisar Endereço/Localização**, o usuário pode informar:

> 👉 O sistema **identifica automaticamente o tipo de endereço informado**, não sendo necessário selecionar o tipo manualmente.

<table><thead><tr><th valign="middle">Endereço/Localização</th><th>Exemplo</th></tr></thead><tbody><tr><td valign="middle">Endereço arquivístico</td><td><kbd>EDG2R02A04M004CSOS</kbd></td></tr><tr><td valign="middle">Palete</td><td><kbd>PLTG140114SOS</kbd></td></tr><tr><td valign="middle">Em Tratamento</td><td><kbd>ETRATAG120720SOS</kbd></td></tr><tr><td valign="middle">Em Trânsito</td><td><kbd>ETRANSG20200SOS</kbd></td></tr><tr><td valign="middle">Aguardando Transporte</td><td><kbd>EAGTRP...</kbd></td></tr></tbody></table>

{% hint style="info" %}
**🔍 Pesquisa por endereço parcial (endereçamento arquivístico)**

Também é possível realizar a pesquisa informando **parte do endereço arquivístico**, por exemplo:

* `EDG2R10` → retorna todas as caixas da **Rua 10 do Galpão G2**
* `EDG2R10A02M010` → retorna todas as caixas do **Módulo 010, Andar 02, Rua 10 do Galpão G2**

⚠️ **Atenção:**\
Quando a pesquisa envolve um grande volume de dados, o sistema pode solicitar que o resultado seja gerado **exclusivamente via relatório em Excel**, exibindo a mensagem:

<mark style="color:$warning;">`“A consulta realizada tem um volume elevado de dados. Por favor, baixe o arquivo em Excel.”`</mark>
{% endhint %}

EDG2R10

#### 📋 Como funciona a pesquisa

{% stepper %}
{% step %}
Digite o código do endereço (Ex.: prateleira, caixa, estante, pallet).

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Clique em  ![](<../.gitbook/assets/image (329).png>) .

Na grid abaixo, será exibido o número total de itens encontrados na localização.

<figure><img src="../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Caso precise, gere uma planilha Excel com os dados exibidos na pesquisa, facilitando conferência do inventário. Clique em  ![](<../.gitbook/assets/image (330).png>) .

<details>

<summary>📥 Exportar resultados para Excel</summary>

Após realizar a pesquisa, o usuário pode clicar em **Exportar para Excel**.

* O arquivo é gerado **em segundo plano**;
* A interface não é bloqueada;
* O relatório fica disponível na **Central de Downloads**;

</details>
{% endstep %}
{% endstepper %}

{% hint style="success" %}
Ação concluída!
{% endhint %}



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
