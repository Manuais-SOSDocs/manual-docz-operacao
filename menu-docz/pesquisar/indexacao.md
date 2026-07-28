---
hidden: true
icon: file-lines
---

# Indexação

A funcionalidade de Indexação é utilizada para associar informações (metadados) aos documentos digitais ou físicos armazenados no sistema.

**Fluxo de uso:**

1. Na **Pesquisa**, o usuário clica no ícone <img src="../../.gitbook/assets/image (427).png" alt="" data-size="line"> vinculado ao documento.
2. É direcionado para a tela **Indexação**, onde são listadas as indexações atribuídas a ele.
3. O usuário deve clicar em <mark style="color:blue;">**Acessar Indexação**</mark>.

<figure><img src="../../.gitbook/assets/image (424).png" alt=""><figcaption></figcaption></figure>

4. Em seguida, será aberta a tela do **Formulário de Indexação**, onde é possível:

* Visualizar a digitalização do documento e preencher os campos de metadados solicitados;
* Ou, em casos específicos, consultar o documento físico para inserir os dados (dependendo do projeto).

5. Após preencher os campos, o usuário deve clicar em <mark style="color:green;">**Salvar/Confirmar**</mark>.

<figure><img src="../../.gitbook/assets/image (426).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Observação:**

* Se a **indexação for individual**, o processo é finalizado após a confirmação.
* Se a **indexação for distribuída em lote**, ao clicar em **Salvar/Confirmar**, o sistema encaminha automaticamente o usuário para o próximo formulário e documento da fila, até a conclusão do lote.
* Os **campos do formulário** a serem preenchidos podem variar de acordo com as **configurações definidas em cada projeto**.
{% endhint %}

### 🤖 Indexação por IA (Docfy + DocZ)

A funcionalidade de **Indexação por Inteligência Artificial (IA)** permite automatizar o preenchimento de metadados dos documentos por meio da integração entre o DocZ e o DocFy.

Quando um documento atinge a etapa documental configurada para processamento por IA, o DocZ encaminha o arquivo ao [**DocFy**](https://manualsosdocs.gitbook.io/adm-docz/projetos/formularios#entenda-o-que-e-o-docfy), responsável por analisar o conteúdo e extrair as informações definidas para o projeto. Após a extração, os metadados são devolvidos ao DocZ e preenchidos automaticamente no formulário de indexação correspondente.

Em seguida, um usuário com permissão de **Indexador** acessa a tela de indexação para conferir, corrigir e confirmar as informações extraídas antes da conclusão da indexação.

Essa abordagem combina automação e validação humana, reduzindo o esforço operacional e aumentando a produtividade sem comprometer a qualidade dos dados indexados.

#### Como Funciona para o Usuário <a href="#como-funciona-para-o-usuario" id="como-funciona-para-o-usuario"></a>

Após a configuração da funcionalidade no projeto, os usuários com permissão de **Indexador/Validador** passam a visualizar a opção:

**Indexação → Validar Extração por IA**

Ao acessar a funcionalidade, o sistema apresenta em uma única tela o documento PDF e os metadados previamente extraídos pelo **DocFy**. Dessa forma, o usuário pode conferir as informações sem a necessidade de navegar entre diferentes telas ou módulos.

Durante a validação, o usuário poderá:

* Conferir os dados extraídos pela IA;
* Corrigir informações identificadas incorretamente;
* Complementar campos não preenchidos;
* Ajustar classificações, descrições e demais metadados configurados no formulário;
* Confirmar a validação do documento.

Após selecionar **Validar Indexação**, o sistema salva as informações e disponibiliza automaticamente um novo documento para validação, quando houver itens pendentes.

<table data-card-size="large" data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><h4><strong>Distribuição Automática dos Documentos</strong></h4><p>A validação da extração por IA não utiliza filas visíveis ao usuário.</p><p>Os documentos são disponibilizados automaticamente pelo sistema conforme a configuração do formulário, utilizando o mecanismo de <strong>Distribuição Aleatória</strong>. A cada validação concluída, o DocZ busca um novo documento elegível para conferência.</p><p>Para garantir a integridade do processo, um mesmo documento não pode ser disponibilizado simultaneamente para mais de um usuário. Enquanto estiver em validação, o documento permanece reservado ao usuário responsável pela atividade.</p></td></tr><tr><td><h4><strong>Histórico de Validações</strong></h4><p>Os documentos já validados são exibidos na grade inferior da tela, permitindo consultas e revisões posteriores.</p><p>Quando necessário, o usuário poderá utilizar a ação <strong>Editar</strong> para reabrir um documento validado e realizar ajustes nos metadados, mantendo a flexibilidade operacional do processo.</p></td></tr></tbody></table>



<a href="./#acoes-disponiveis-localizadas-acima-da-grade-projeto" class="button secondary" data-icon="circle-left">Voltar</a>
