---
description: MENU > GESTÃO DE OPERAÇÕES > TRILHA DE AUDITORIA
---

# Trilha de Auditoria

A **Trilha de Auditoria** permite consultar e acompanhar todas as ações realizadas no sistema, garantindo **rastreabilidade, transparência e controle** sobre as operações executadas por usuários, clientes e objetos.

<figure><img src="../../.gitbook/assets/image (491).png" alt=""><figcaption></figcaption></figure>

#### 📝 Passo a passo para consulta da Trilha de Auditoria

{% stepper %}
{% step %}
Ao acessar a tela, é exibido um **formulário de pesquisa**, que possibilita localizar registros específicos conforme os filtros selecionados.

<figure><img src="../../.gitbook/assets/image (302).png" alt=""><figcaption></figcaption></figure>
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

<figure><img src="../../.gitbook/assets/image (303).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary>👤 Cliente</summary>

**Objetivo:** rastrear todas as ações feitas por um cliente específico no sistema.

Quando a trilha é filtrada por **Cliente**, os campos disponíveis são:

* **Cliente:** campo de seleção de cliente.
* **Ação:** ações realizadas pelo cliente. <sup><sub><kbd>(este campo é obrigatório nesta opção)<kbd><sub></sup>
* **Data Inicial e Data Final:** para delimitar o período da busca. <sup><sub><kbd>(este campo é obrigatório nesta opção)<kbd><sub></sup>

<figure><img src="../../.gitbook/assets/image (304).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary>🙍‍♂️ Usuário</summary>

&#x20;**Objetivo:** verificar o que um usuário fez em nome de um cliente (ou em nome próprio), incluindo ações detalhadas por data.

Ao selecionar **Usuário**, os seguintes campos aparecem:

* **Usuário:** seleção de usuário do sistema.
* **Cliente:** também pode ser filtrado por cliente vinculado.
* **Ação (opcional):** ações realizadas pelo cliente.&#x20;
* **Data Inicial e Data Final:** para delimitar o período da busca. <sup><sub><kbd>(este campo é obrigatório nesta opção)<kbd><sub></sup>

<figure><img src="../../.gitbook/assets/image (305).png" alt=""><figcaption></figcaption></figure>

</details>

<details>

<summary>📤 Compartilhou Documento</summary>

**Objetivo:** auditar documentos que foram compartilhados, provavelmente com informações como destinatário, tipo de acesso, etc.

Aqui o foco é nas ações de compartilhamento, com os campos:

* **Identificador SOS:** campo para digitar o ID do objeto.
* **Data Inicial e Data Final:** para delimitar o período da busca.&#x20;

<figure><img src="../../.gitbook/assets/image (306).png" alt=""><figcaption></figcaption></figure>

</details>
{% endstep %}

{% step %}
Depois de preencher o formulário, clique em  <img src="../../.gitbook/assets/image (308).png" alt="" data-size="original"> .&#x20;
{% endstep %}

{% step %}
Os resultados serão exibidos automaticamente na grid abaixo.

<figure><img src="../../.gitbook/assets/image (307).png" alt=""><figcaption></figcaption></figure>

> A consulta possui limite de até 500 registros. No canto superior direito da grid, é possível ajustar a quantidade de itens exibidos por página.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
Ação concluída.
{% endhint %}



<details>

<summary><strong>Campos da Grid da Trilha de Auditoria</strong></summary>

A tabela abaixo descreve os campos exibidos na grid da Trilha de Auditoria e a finalidade de cada informação registrada.

<table><thead><tr><th width="151.77777099609375">Campo</th><th>Descrição</th></tr></thead><tbody><tr><td><strong>ID Log</strong></td><td>Identificador único do registro de auditoria, gerado automaticamente pelo sistema.</td></tr><tr><td><strong>Tipo de Log</strong></td><td>Categoria do evento registrado, como <strong>Usuário</strong>, <strong>Grupo de Usuários</strong>, <strong>Solicitação</strong>, <strong>Auditoria</strong>, entre outras, conforme a operação executada.</td></tr><tr><td><strong>Data/Hora</strong></td><td>Data e horário em que a ação foi realizada. O preenchimento é automático.</td></tr><tr><td><strong>Origem (IP)</strong></td><td>Endereço IP do dispositivo que originou a operação. Registrado automaticamente para fins de rastreabilidade.</td></tr><tr><td><strong>Objeto</strong></td><td>Elemento afetado pela ação, como documento, caixa, usuário, grupo, projeto ou outra entidade do sistema.</td></tr><tr><td><strong>Ação</strong></td><td>Operação executada pelo usuário ou pelo sistema, como criação, alteração, exclusão, movimentação, bloqueio ou tentativa de acesso.</td></tr><tr><td><strong>Cliente</strong></td><td>Cliente ao qual a operação está vinculada. Quando aplicável, corresponde ao cliente selecionado no contexto da ação.</td></tr><tr><td><strong>Projeto</strong></td><td>Projeto relacionado ao registro de auditoria. Caso a ação não esteja vinculada a um projeto específico, o campo poderá ser apresentado como <strong>N/A</strong>.</td></tr><tr><td><strong>Usuário</strong></td><td>Nome do usuário responsável pela execução da ação.</td></tr><tr><td><strong>ID Usuário</strong></td><td>Identificador único do usuário responsável pela operação.</td></tr><tr><td><strong>Observações</strong></td><td>Informações complementares sobre o evento registrado, como detalhes da operação, justificativas, valores alterados, mensagens de sucesso, falha, bloqueios ou outras informações relevantes para auditoria.</td></tr></tbody></table>

</details>







<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
