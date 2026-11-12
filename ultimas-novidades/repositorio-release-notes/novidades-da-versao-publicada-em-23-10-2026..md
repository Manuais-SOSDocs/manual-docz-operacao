---
description: 'Versão: Docz v:2026.10.22.23.38bd22c0'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 23/10/2026.

Esta atualização inclui o lançamento da primeira versão do Módulo Sentinela para acompanhamento operacional das esteiras de documentos e caixas e amplia os recursos de indexação, análise da validação por IA e exportação de informações. Também traz a configuração dos termos de uso, melhorias no carregamento do Painel e na auditoria, além de correções operacionais.

### 📦 Novas funcionalidades

#### 🆕 Sentinela: monitoramento das esteiras de documentos e caixas

Nesta primeira versão, o módulo Sentinela permite o acompanhamento das status de documentos e caixas, com configuração e consulta individualizadas por projeto.

Na configuração, é possível definir quais etapas documentais e status da gestão documental serão monitorados, e os tempos máximos de permanência utilizados para identificar objetos sem avanço.

O dashboard apresenta separadamente as esteiras de Documentos e Caixas, com indicadores para cada posição monitorada.

Também é possível habilitar as situações gerenciais Com movimentação no período, Sem movimentação no período, Tempo excedido na posição, Possível gargalo e Impedimento comprovado, com configuração de tempo em minutos nas opções aplicáveis.

#### 📝 Indexação: preenchimento automático da origem do documento

O DocZ passa a permitir que a Origem do documento seja preenchida automaticamente com a informação cadastrada na caixa. Ao bipar o código da caixa durante a indexação, o sistema recupera essa informação e preenche o campo antes da finalização.

O recurso depende da habilitação do campo "Origem" e da ativação da opção "Preencher origem do documento com a origem da caixa", conforme configuração do projeto.

A melhoria reduz o preenchimento manual e favorece a padronização das informações entre caixas e documentos.

#### 📊 Painel de IA: análise por usuário e campos ausentes

O Painel Gerencial de Extração e Validação por IA passa a disponibilizar duas novas análises:

* Por Usuário: apresenta documentos e campos avaliados, valores mantidos, corrigidos e preenchidos manualmente, além das divergências identificadas. O filtro Usuário Validador permite direcionar a consulta.
* Campos Ausentes: identifica os metadados não extraídos pela IA, distinguindo os preenchidos manualmente daqueles que permaneceram vazios por serem opcionais. Também apresenta obrigatoriedade, taxa de ausência e nível de atenção.

As consultas respeitam os clientes, projetos e filtros autorizados para o usuário.

#### 📄 Configuração de Termos de Uso e Política de Privacidade

Usuários com permissão de administrador agora podem cadastrar, editar e publicar o conteúdo dos Termos de Uso e Política de Privacidade pela interface do sistema.

#### 📑 Exportação dos metadados dos arquivos para Excel

Na visualização de objetos, a aba Arquivos passa a contar com a opção Exportar para Excel, permitindo gerar uma planilha com os metadados dos arquivos vinculados diretamente ao documento ou à caixa selecionada.

### 🛠️ Melhorias

#### ✍️ Embarque Dinâmico de Metadados: informações de pastas e pesquisa de campos

A configuração do Embarque Dinâmico de Metadados passa a disponibilizar a seção Informações de pastas, permitindo utilizar os nomes das pastas do projeto nas regras de embarque.

A interface também recebe pesquisa de campos e ordenação alfabética, facilitando a localização das informações em projetos com muitos metadados.

#### 📦 Download em Lote: escolha da organização dos arquivos

Ao solicitar o Download em Lote, o usuário poderá escolher entre:

* Exportação Completa: organiza os arquivos em uma pasta para cada documento.
* Exportação Direta: reúne todos os arquivos diretamente no ZIP, sem pastas individuais.

Na Exportação Direta, os nomes dos arquivos recebem o Identificador SOS da DC antes do nome original, facilitando a identificação do documento de origem e evitando conflitos entre arquivos de documentos distintos com nomes iguais.

#### ⚡ Otimização do carregamento do Painel

Os indicadores que exigem maior processamento passam a utilizar dados previamente consolidados, com atualização automática periódica, tornando o carregamento do Painel mais ágil, especialmente em projetos com grande volume de dados.

O Painel também passa a exibir a data e hora da última atualização e a ação Atualizar, que permite solicitar o processamento completo dos indicadores. Ao utilizar essa opção, o usuário será informado de que a atualização poderá levar alguns minutos.

#### 🔎 Ampliação da trilha de auditoria

A trilha de auditoria do passa a registrar mais ações administrativas, incluindo alterações de dados, permissões, grupos e projetos na funcionalidade Gerenciar Usuários, além de tentativas de acesso não autorizado.

#### 🆕 Confirmação de assinatura com certificado

A mensagem de confirmação de assinatura passa a utilizar a identificação Certificado do usuário, tornando mais clara a indicação do certificado utilizado na operação.

### 🐞 Correções

<table data-card-size="large" data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><strong>Histórico da Etapa Documental</strong></p><p>Corrigida a exibição das alterações desse metadado na aba Versões, permitindo consultar seu histórico junto aos demais campos.</p></td></tr><tr><td><p><strong>Layout dos campos de indexação</strong></p><p>Corrigidos os desalinhamentos e as quebras de layout no formulário de cadastro de campos da indexação de arquivos.<br></p></td></tr><tr><td><p><strong>Layout da Tabela de Temporalidade</strong></p><p>Ajustados o alinhamento e o espaçamento do campo Sigilo Associado à Classe na janela de edição.</p></td></tr><tr><td><p><strong>Validação da data de eventos</strong></p><p>Corrigida a validação para impedir o cadastro ou a edição de eventos com data anterior à data de produção do documento.</p></td></tr><tr><td><p><strong>Relatório de Documentos por Classe Documental</strong></p><p>Corrigida a geração do arquivo Excel do Relatório 11, eliminando a falha que impedia sua abertura após o download.</p></td></tr><tr><td><p><strong>Gerenciar Digitalizações</strong></p><p>Tratado o erro 500 relacionado ao acesso à funcionalidade no módulo de Gestão Documental.<br></p></td></tr><tr><td><p><strong>Controles da tela de indexação</strong></p><p>Ajustada a tradução dos controles de pesquisa e paginação, que eram apresentados em inglês e passam a ser exibidos em português.</p></td></tr><tr><td><p><strong>Consulta de Fotolabels</strong></p><p>Restabelecida a opção Personalizado no filtro Data de modificação, permitindo consultar as Fotolabels por um período definido pelo usuário.</p></td></tr><tr><td><p><strong>Mapa de ocupação do armazém</strong></p><p>Corrigida a falha que deixava a área do mapa em branco no DocZ interno, restabelecendo a exibição das ruas, módulos, níveis e indicadores de ocupação.</p></td></tr></tbody></table>



🚀 Seguimos evoluindo o DocZ com foco em conformidade SBIS, segurança digital, rastreabilidade, integração e eficiência operacional.

{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Voltar</a>
