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



### Mais informações:

<details>

<summary><strong>Ações Registradas na Trilha de Auditoria</strong></summary>

A Trilha de Auditoria registra automaticamente as operações realizadas pelos usuários no DocZ, permitindo acompanhar quem executou cada ação, quando ela ocorreu e sobre qual objeto ela foi realizada.

As ações registradas variam conforme as permissões do usuário e os módulos utilizados, abrangendo desde consultas até alterações, exclusões e processos de gestão documental.

#### Principais ações registradas

<table><thead><tr><th width="173.1112060546875">Categoria</th><th>Ações registradas</th></tr></thead><tbody><tr><td><strong>Consulta</strong></td><td>Visualização e abertura de documentos, caixas, processos, dossiês, mídias e demais objetos do sistema.</td></tr><tr><td><strong>Cadastro e Alteração</strong></td><td>Criação, edição e atualização de documentos, caixas, processos, etapas documentais e demais registros.</td></tr><tr><td><strong>Arquivos</strong></td><td>Upload, substituição, remoção, inativação e visualização de arquivos digitais.</td></tr><tr><td><strong>Assinaturas Digitais</strong></td><td>Aplicação de chancela, assinatura digital, validação, revalidação, emissão de certificados e registro de falhas na validação.</td></tr><tr><td><strong>Compartilhamento</strong></td><td>Compartilhamento de documentos e geração de links para acesso externo.</td></tr><tr><td><strong>Relatórios</strong></td><td>Geração e download de relatórios e relatórios de assinaturas.</td></tr><tr><td><strong>Operações em Lote</strong></td><td>Atualização de caixas e documentos em lote.</td></tr><tr><td><strong>Gestão Documental</strong></td><td>Destinação documental, recolhimento, expurgo, preservação de metadados e atualização de status.</td></tr><tr><td><strong>Exclusões e Restaurações</strong></td><td>Exclusão e restauração de documentos e caixas, quando permitido.</td></tr><tr><td><strong>Importações</strong></td><td>Upload de arquivos em Ordens de Serviço, agendamento e cancelamento de importações.</td></tr></tbody></table>

</details>

<details>

<summary><strong>Campos da Grid da Trilha de Auditoria</strong></summary>

A tabela abaixo descreve os campos exibidos na grid da Trilha de Auditoria e a finalidade de cada informação registrada.

<table><thead><tr><th width="151.77777099609375">Campo</th><th>Descrição</th></tr></thead><tbody><tr><td><strong>ID Log</strong></td><td>Identificador único do registro de auditoria, gerado automaticamente pelo sistema.</td></tr><tr><td><strong>Tipo de Log</strong></td><td>Categoria do evento registrado, como <strong>Usuário</strong>, <strong>Grupo de Usuários</strong>, <strong>Solicitação</strong>, <strong>Auditoria</strong>, entre outras, conforme a operação executada.</td></tr><tr><td><strong>Data/Hora</strong></td><td>Data e horário em que a ação foi realizada. O preenchimento é automático.</td></tr><tr><td><strong>Origem (IP)</strong></td><td>Endereço IP do dispositivo que originou a operação. Registrado automaticamente para fins de rastreabilidade.</td></tr><tr><td><strong>Objeto</strong></td><td>Identifica o elemento sobre o qual a ação foi executada. Atualmente esse campo pode representar tanto um <strong>objeto documental</strong> (Caixa, Documento Classificado – DC, Arquivo etc.) quanto uma <strong>entidade do sistema</strong>, como Certificados Digitais, Usuários, Permissões, Pacotes pSIP e outros recursos administrativos. </td></tr><tr><td><strong>Ação</strong></td><td>Operação executada pelo usuário ou pelo sistema, como criação, alteração, exclusão, movimentação, bloqueio ou tentativa de acesso.</td></tr><tr><td><strong>Cliente</strong></td><td>Cliente ao qual a operação está vinculada. Quando aplicável, corresponde ao cliente selecionado no contexto da ação.</td></tr><tr><td><strong>Projeto</strong></td><td>Projeto relacionado ao registro de auditoria. Caso a ação não esteja vinculada a um projeto específico, o campo poderá ser apresentado como <strong>N/A</strong>.</td></tr><tr><td><strong>Usuário</strong></td><td>Nome do usuário responsável pela execução da ação.</td></tr><tr><td><strong>ID Usuário</strong></td><td>Identificador único do usuário responsável pela operação.</td></tr><tr><td><strong>Número da O.S.</strong></td><td>Número da Ordem de Serviço relacionada à operação, quando a ação estiver vinculada a uma solicitação.</td></tr><tr><td><strong>Observações</strong></td><td>Informações complementares sobre o evento registrado, como detalhes da operação, justificativas, valores alterados, mensagens de sucesso, falha, bloqueios ou outras informações relevantes para auditoria.</td></tr></tbody></table>

</details>

<details>

<summary><strong>Informações registradas em Observações</strong></summary>

O campo **Observações** apresenta detalhes específicos da ação executada, permitindo compreender exatamente o que foi alterado.

Dependendo da operação realizada, poderão ser registrados:

* valores anteriores e novos dos campos alterados;
* permissões adicionadas ou removidas;
* projetos vinculados ou removidos do usuário;
* alteração do prazo de acesso aos projetos;
* usuários adicionados ou removidos de grupos;
* dados cadastrados durante a criação de usuários ou grupos.

Essas informações tornam a auditoria mais detalhada e facilitam processos de rastreamento, investigação e conformidade.

</details>

{% hint style="info" %}
## Segurança das informações

A Trilha de Auditoria registra apenas as informações necessárias para comprovar a operação executada.

Por questões de segurança, dados sensíveis, como senhas, tokens, certificados e chaves de autenticação, **não são armazenados** nos registros de auditoria, mesmo quando fazem parte da operação realizada.
{% endhint %}



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
