---
description: MENU > GESTÃO DE OPERAÇÕES > TRILHA DE AUDITORIA
---

# Trilha de Auditoria

A **Trilha de Auditoria** permite consultar e acompanhar todas as ações realizadas no sistema, garantindo **rastreabilidade, transparência e controle** sobre as operações executadas por usuários, clientes e objetos.

<figure><img src="../.gitbook/assets/image (491).png" alt=""><figcaption></figcaption></figure>

#### 📝 Passo a passo para consulta da Trilha de Auditoria

{% stepper %}
{% step %}
Ao acessar a tela, é exibido um **formulário de pesquisa**, que possibilita localizar registros específicos conforme os filtros selecionados.

<figure><img src="../.gitbook/assets/image (302).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Cada opção de filtro abre um conjunto de campos específicos para preenchimento, conforme o tipo de consulta desejada, como data, ação, identificador, cliente ou usuário.

<details>

<summary>📃 Objeto</summary>

**Objetivo:** identificar as ações que foram feitas com um determinado objeto.

Quando a trilha é filtrada por **Objeto**, aparecem os seguintes campos para preenchimento:

* **Identificador SOS:** campo para digitar o ID do objeto.
* **Ação (opcional):** lista suspensa com as ações executadas (ex: criar, editar, excluir etc.).
* **Data Inicial e Data Final(opcional):** para delimitar o período da busca.

<figure><img src="../.gitbook/assets/image (303).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary>👤 Cliente</summary>

**Objetivo:** rastrear todas as ações feitas por um cliente específico no sistema.

Quando a trilha é filtrada por **Cliente**, os campos disponíveis são:

* **Cliente:** campo de seleção de cliente.
* **Ação:** ações realizadas pelo cliente. <sup><sub><kbd>(este campo é obrigatório nesta opção)<kbd><sub></sup>
* **Data Inicial e Data Final:** para delimitar o período da busca. <sup><sub><kbd>(este campo é obrigatório nesta opção)<kbd><sub></sup>

<figure><img src="../.gitbook/assets/image (304).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary>🙍‍♂️ Usuário</summary>

&#x20;**Objetivo:** verificar o que um usuário fez em nome de um cliente (ou em nome próprio), incluindo ações detalhadas por data.

Ao selecionar **Usuário**, os seguintes campos aparecem:

* **Usuário:** seleção de usuário do sistema.
* **Cliente:** também pode ser filtrado por cliente vinculado.
* **Ação (opcional):** ações realizadas pelo cliente.&#x20;
* **Data Inicial e Data Final:** para delimitar o período da busca. <sup><sub><kbd>(este campo é obrigatório nesta opção)<kbd><sub></sup>

<figure><img src="../.gitbook/assets/image (305).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary>📤 Compartilhou Documento</summary>

**Objetivo:** auditar documentos que foram compartilhados, provavelmente com informações como destinatário, tipo de acesso, etc.

Aqui o foco é nas ações de compartilhamento, com os campos:

* **Identificador SOS:** campo para digitar o ID do objeto.
* **Data Inicial e Data Final:** para delimitar o período da busca.&#x20;

<figure><img src="../.gitbook/assets/image (306).png" alt=""><figcaption></figcaption></figure>

</details>
{% endstep %}

{% step %}
Depois de preencher o formulário, clique em  <img src="../.gitbook/assets/image (308).png" alt="" data-size="original"> .&#x20;
{% endstep %}

{% step %}
Os resultados serão exibidos automaticamente na grid abaixo.

<figure><img src="../.gitbook/assets/image (307).png" alt=""><figcaption></figcaption></figure>

> A consulta possui limite de até 500 registros. No canto superior direito da grid, é possível ajustar a quantidade de itens exibidos por página.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
Ação concluída.
{% endhint %}



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
