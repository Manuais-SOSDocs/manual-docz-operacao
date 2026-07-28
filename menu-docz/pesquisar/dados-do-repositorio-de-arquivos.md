---
hidden: true
icon: database
---

# Dados do repositório de arquivos

{% hint style="warning" %}
Esta funcionalidade está disponível apenas para usuários que possuem a **permissão&#x20;**_**Emitir Relatório de Arquivo**_ habilitada.
{% endhint %}

A funcionalidade **Repositório DocZ File Service** permite acompanhar e analisar os arquivos digitais armazenados no ambiente DocZ, fornecendo informações sobre ocupação do repositório, volume de arquivos, quantidade de imagens e utilização de espaço por projeto.

Esta funcionalidade atua como uma camada de monitoramento e consulta do **DocZ File Service**, serviço especializado responsável pelo armazenamento e gerenciamento técnico dos arquivos digitais do sistema.

<details>

<summary><em><mark style="color:blue;"><strong>O que é o DocZ File Service?</strong></mark></em></summary>

O **DocZ File Service** é um serviço especializado da arquitetura DocZ responsável pela gestão dos arquivos binários armazenados na plataforma, como:

* PDF
* DOCX
* XLSX
* JPG
* PNG
* TIFF
* Outros formatos digitais suportados

Sua função é armazenar, versionar, recuperar e controlar tecnicamente os arquivos vinculados aos registros do sistema, mantendo-os segregados do banco de dados principal.

<table data-card-size="large" data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><strong>Principais Responsabilidades</strong></p><ul><li>Armazenamento de arquivos digitais;</li><li>Controle de versões;</li><li>Recuperação de documentos;</li><li>Download controlado;</li><li>Geração de links temporários;</li><li>Registro de logs técnicos;</li><li>Integração com assinatura digital;</li><li>Distribuição de arquivos para indexação.</li></ul></td></tr><tr><td><p><strong>Limites de Atuação</strong></p><p>O File Service <strong>não</strong>:</p><ul><li>Armazena metadados arquivísticos;</li><li>Executa regras de negócio;</li><li>Controla permissões de usuários;</li><li>Realiza autenticação;</li><li>Integra diretamente com sistemas externos sem mediação do DocZ.</li></ul></td></tr></tbody></table>

Todas as operações são disponibilizadas por API própria e consumidas pelos componentes autorizados da plataforma.

</details>

<figure><img src="../../.gitbook/assets/image (536).png" alt=""><figcaption></figcaption></figure>

#### Funcionalidades Disponíveis:

<details>

<summary>Filtro Projeto</summary>

<figure><img src="../../.gitbook/assets/image (546).png" alt=""><figcaption></figcaption></figure>

O filtro **Projetos** define qual projeto será utilizado como base para a análise do repositório de arquivos no **DocZ File Service**.

Como cada projeto possui sua própria estrutura documental, formulários, metadados e arquivos armazenados, é necessário selecionar um projeto antes de executar qualquer consulta.

</details>

<details>

<summary>Quantidade de Arquivos Ativos</summary>

<figure><img src="../../.gitbook/assets/image (545).png" alt=""><figcaption></figcaption></figure>

Representa o total de arquivos atualmente considerados ativos no projeto.

**O que é um arquivo ativo?**

É a versão mais recente disponível para utilização pelo usuário.

Exemplos:

* Documento original;
* Documento assinado;
* Documento convertido.

Quando ocorre versionamento, apenas a versão vigente permanece marcada como ativa.

</details>

<details>

<summary>Volume de Imagens</summary>

<figure><img src="../../.gitbook/assets/image (544).png" alt=""><figcaption></figcaption></figure>

Apresenta a quantidade total de imagens armazenadas no projeto.

Podem ser contabilizadas:

* Imagens digitalizadas;
* Anexos de documentos;
* Foto Label;
* Arquivos de imagem vinculados aos objetos.

</details>

<details>

<summary>Ocupação do Repositório (GB)</summary>

<figure><img src="../../.gitbook/assets/image (543).png" alt=""><figcaption></figcaption></figure>

Exibe o espaço efetivamente utilizado pelos arquivos armazenados no File Service.

Essa informação é importante para:

* Monitoramento da capacidade;
* Gestão de armazenamento;
* Controle contratual;
* Planejamento de expansão.

Durante os treinamentos do SIGAD foi destacado que essa informação também pode ser utilizada para acompanhamento do consumo de armazenamento por cliente.

</details>

<details>

<summary>Subfiltros</summary>

<figure><img src="../../.gitbook/assets/image (542).png" alt=""><figcaption></figcaption></figure>

Após selecionar o projeto, a seção **Subfiltro** permite restringir a análise dos arquivos armazenados no DocZ File Service. Por meio desses filtros, é possível direcionar a consulta para uma pasta específica da estrutura documental, definir um período de análise e escolher qual versão dos arquivos deverá ser considerada nos resultados.

* **Pastas:** permite consultar apenas os arquivos vinculados a uma determinada pasta do projeto, como Documentos, Contratos, Dossiês RH ou outras estruturas cadastradas.
* **Data Inicial:** define a data de início do período que será considerado na consulta.
* **Data Final:** define a data final do período analisado.
* **Versão:** permite selecionar se a consulta utilizará a versão mais recente dos arquivos ou a primeira versão armazenada no repositório.

</details>

<details>

<summary>Grade de resultados</summary>

<figure><img src="../../.gitbook/assets/image (541).png" alt=""><figcaption></figcaption></figure>

Após a execução dos filtros, a seção **Arquivos** apresenta os resultados encontrados no repositório do DocZ File Service. Cada linha da grade representa um arquivo armazenado e disponibiliza informações técnicas que auxiliam no controle, auditoria e análise do conteúdo digital do projeto.

As informações exibidas incluem:

* **Projeto:** projeto ao qual o arquivo está vinculado.
* **Etiqueta:** identificador único do objeto no DocZ.
* **Arquivo:** nome físico do arquivo armazenado no repositório.
* **Hash:** código único gerado pelo sistema para garantir a integridade e rastreabilidade do arquivo.
* **Tipologia:** tipologia documental associada ao arquivo, quando configurada.
* **Imagem:** quantidade de imagens ou páginas que compõem o arquivo.
* **Tamanho (MB):** espaço ocupado pelo arquivo no repositório.
* **Versão:** versão do arquivo armazenada no File Service.
* **Situação:** status técnico atual do arquivo no repositório.

A grade também disponibiliza recursos de paginação e pesquisa rápida, permitindo localizar registros específicos dentro dos resultados retornados pela consulta.

Esta visualização é especialmente útil para auditorias técnicas, conferência de arquivos armazenados, análise de ocupação do repositório e validação de informações antes da geração de relatórios ou exportações.

</details>

<details>

<summary>Botões disponíveis</summary>

<table data-card-size="large" data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><img src="../../.gitbook/assets/image (537).png" alt=""><br>Aplica os filtros informados e atualiza os dados apresentados na consulta.</td></tr><tr><td><img src="../../.gitbook/assets/image (538).png" alt=""><br>Gera uma planilha contendo as informações dos arquivos encontrados.</td></tr><tr><td><p><img src="../../.gitbook/assets/image (539).png" alt=""><br>Gera um relatório detalhado combinando:</p><ul><li>Informações do Objeto</li><li>Informações do Arquivo</li></ul><p>Por se tratar de um relatório mais pesado, normalmente é processado em segundo plano e disponibilizado posteriormente para download.</p></td></tr><tr><td><img src="../../.gitbook/assets/image (540).png" alt="" data-size="original"><br>Direciona o usuário para a Central de Downloads do DocZ, onde ficam disponíveis os relatórios processados em segundo plano.</td></tr></tbody></table>

</details>



<a href="./#acoes-disponiveis-localizadas-acima-da-grade-projeto" class="button secondary" data-icon="circle-left">Voltar</a>
