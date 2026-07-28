# Embarque de metadados

A funcionalidade **Embarque de Metadados** permite configurar, de forma dinâmica e por projeto, quais informações serão incorporadas aos arquivos PDF gerados pelo DocZ.

Por meio dessa configuração, é possível definir como metadados como **Assunto, Autor, Classe, Tipo Documental, Prazo de Guarda, Data de Produção** e outros atributos serão preenchidos automaticamente utilizando informações existentes nos campos de indexação do projeto.

A solução foi desenvolvida para atender requisitos de governança documental e aderência ao **Decreto nº 10.278/2020**, garantindo que os documentos digitalizados possam conter informações complementares padronizadas e rastreáveis.

![](https://manualsosdocs.gitbook.io/adm-docz/~gitbook/image?url=https%3A%2F%2F2165951091-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FH2zBMzYHjbRsfnTeRGr3%252Fuploads%252F6bcezgFIFPHeJFKZeDGW%252Fimage.png%3Falt%3Dmedia%26token%3D12a00674-ebbb-473e-b126-b54ffbc180f7\&width=768\&dpr=3\&quality=100\&sign=8ec87431\&sv=2)

#### Como Funciona? <a href="#como-funciona" id="como-funciona"></a>

O embarque de metadados é baseado em regras configuradas por projeto.

Quando um documento é processado, o DocZ analisa as regras cadastradas e identifica qual delas deve ser aplicada. A partir dessa definição, o sistema monta automaticamente os metadados do PDF utilizando os campos configurados pelo administrador.

A configuração pode ser:

* **Genérica**, aplicada a todos os documentos do projeto;
* **Específica**, aplicada apenas quando determinada condição for atendida.

Exemplo:

```
Tipo Documental = Contrato
        ↓
Aplicar Regra "Contratos"

Tipo Documental = Prontuário
        ↓
Aplicar Regra "Prontuários"

Sem regra específica
        ↓
Aplicar Regra Genérica
```

#### Regras de Embarque

Toda configuração é baseada em **Regras de Embarque de Metadados**.

Cada regra define:

* Quando ela será aplicada;
* Quais metadados serão embarcados;
* De onde virão os valores;
* Como o sistema deverá tratar campos vazios;
* Como o valor final será formatado.

<details>

<summary>Regra Genérica</summary>

Todo projeto possui automaticamente uma **Regra Genérica**, criada pelo sistema.

Essa regra funciona como comportamento padrão quando nenhuma regra específica for encontrada.

Características:

* Criada automaticamente;
* Permanece ativa;
* Não possui chave de decisão;
* Não pode ser removida quando for a única regra do projeto.

</details>

<details>

<summary>Regras Dinâmicas</summary>

Além da regra genérica, é possível criar regras específicas para diferentes cenários.

Exemplos:

* Tipo Documental = Contrato;
* Tipo Documental = Nota Fiscal;
* Status = Arquivado;
* Classe = Recursos Humanos.

Dessa forma, cada conjunto documental pode possuir seus próprios critérios de composição dos metadados.

</details>

#### Configuração das Regras de Embarque

<details>

<summary>Configuração da Regra</summary>

Ao selecionar uma regra, a tela apresenta os seguintes parâmetros:

<table><thead><tr><th width="182">Campo</th><th>Descrição</th></tr></thead><tbody><tr><td><strong>Projeto</strong></td><td>Projeto ao qual a configuração de embarque de metadados pertence.</td></tr><tr><td><strong>Valor da Chave</strong></td><td>Nome da regra cadastrada. Exemplos: Contratos, Prontuários, RH, Regra Genérica.</td></tr><tr><td><strong>Chave de Decisão</strong></td><td>Campo utilizado para determinar quando a regra será aplicada. Exemplos: Tipo Documental, Classe, Status ou Tipologia.</td></tr><tr><td><strong>Selecionar</strong></td><td>Valor que ativará a regra. Exemplo: se a Chave de Decisão for <strong>Tipo Documental</strong> e o valor selecionado for <strong>Contrato</strong>, a regra será aplicada aos documentos classificados como Contrato.</td></tr><tr><td><strong>Status</strong></td><td>Situação da regra. Pode ser <strong>Ativa</strong>, <strong>Inativa</strong> ou <strong>Rascunho</strong>. Apenas regras ativas são consideradas durante o embarque dos metadados.</td></tr></tbody></table>

</details>

<details>

<summary>Campos Configurados por esta Regra</summary>

Nesta seção são definidos os metadados que serão gravados no PDF.

Cada linha representa uma configuração independente.

Exemplo:

```
Metadado PDF: Assunto
        ↓
Campo DocZ: Referência
```

Resultado:

```
Assunto = valor do campo Referência
```

</details>

<details>

<summary>Adicionar Metadado</summary>

Ao clicar em **Adicionar Metadado**, o sistema permite criar uma nova configuração de embarque.

<table><thead><tr><th width="207.3333740234375">Configuração</th><th>Descrição</th></tr></thead><tbody><tr><td><strong>Metadado Destino</strong></td><td>Define qual informação será gravada no PDF. Exemplos: Assunto, Autor, Título, Classe, Tipo Documental, Prazo de Guarda, Data de Produção e Identificador do Documento Digital.</td></tr><tr><td><strong>Origem do Valor</strong></td><td>Define de onde o sistema obterá a informação para preencher o metadado.</td></tr><tr><td><strong>Campo Único</strong></td><td>Utiliza apenas um campo do formulário de indexação. Exemplo: Assunto ← Campo Referência.</td></tr><tr><td><strong>Múltiplos Campos</strong></td><td>Permite combinar até três campos para formar um único valor. Exemplo: Nome + Matrícula + Setor → JOÃO SILVA - 12345 - RH.</td></tr><tr><td><strong>Tratamento de Nulos</strong></td><td>Define como o sistema deve tratar campos sem informação.</td></tr><tr><td><strong>Ignorar Nulos</strong></td><td>Campos vazios são desconsiderados automaticamente, evitando separadores ou espaços desnecessários. Exemplo: João + (vazio) + RH → João - RH.</td></tr><tr><td><strong>Substituir por Valor Padrão</strong></td><td>Quando um campo estiver vazio, o sistema utiliza um valor previamente definido, como "Não Informado".</td></tr><tr><td><strong>Obrigatoriedade</strong></td><td>Define se o metadado deve ser obrigatoriamente composto antes da geração do PDF.</td></tr><tr><td><strong>Formato da Saída</strong></td><td>Permite padronizar a apresentação do valor gerado. Exemplos: Data (DD/MM/AAAA), Caixa Alta, Caixa Baixa e Trim Automático (remoção de espaços excedentes).</td></tr></tbody></table>

</details>

***

#### Exemplo Prático

Suponha um projeto que possua os campos:

* Nome do Colaborador
* Matrícula
* Departamento

E o administrador deseje preencher automaticamente o metadado **Autor**.

Configuração:

```
Metadado Destino: Autor

Origem:
Múltiplos Campos

Campos:
Nome do Colaborador
Matrícula
Departamento

Separador:
-
```

Resultado no PDF:

```
JOÃO SILVA - 12345 - RECURSOS HUMANOS
```

Todo o processo ocorre automaticamente durante a geração do documento, sem necessidade de preenchimento manual pelo usuário.



<a href="/broken/pages/T2lFblRnmenjnUYBbjyM" class="button secondary" data-icon="circle-left">Voltar</a>
