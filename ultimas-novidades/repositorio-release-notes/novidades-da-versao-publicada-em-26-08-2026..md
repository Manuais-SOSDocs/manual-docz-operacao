---
description: 'Versão: Docz v:Docz v:2026.08.25.18.1.5.17.12'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 26/08/2026.

Nesta versão do DocZ iniciamos a disponibilização do novo módulo de Faturamento e ampliamos os recursos de gestão documental em conformidade com o e-ARQ. A atualização também contempla melhorias de usabilidade, permissões e correções em diferentes funcionalidades do sistema.

## 📦 Novas Funcionalidades

#### 💰 Novo Módulo de Faturamento: Cadastro de Serviços e Valores

Foi disponibilizada a primeira funcionalidade do novo módulo de Faturamento do DocZ.\
A atualização permite cadastrar e gerenciar serviços, valores e demais informações necessárias para a estruturação dos processos de faturamento dos clientes.\
Entre as informações disponíveis no cadastro estão:\
Saldo inicial; Preço; Tipo; Tipo de serviço; Categoria do serviço; Códigos de referência; Código NBS.

**🎯 Benefícios**

* Centralização das informações de serviços e valores;
* Maior organização dos dados utilizados no faturamento;
* Estruturação da base necessária para a automação e evolução do módulo de Faturamento.

#### 🗑️ \[E-ARQ] Exclusão Definitiva de Documentos

Foi implementada a funcionalidade de exclusão definitiva de documentos diretamente na Pesquisa de Objetos.\
Quando a visualização de documentos excluídos estiver habilitada, usuários com permissão de Administrador poderão excluir permanentemente documentos que já tenham sido excluídos anteriormente no sistema.\
Para reforçar a segurança da operação, a ação exige confirmação e nova autenticação do usuário. As exclusões realizadas também são registradas na Trilha de Auditoria.

**🎯 Benefícios**

* Maior controle sobre os documentos excluídos;
* Reforço da segurança em operações irreversíveis;
* Maior aderência aos requisitos do e-ARQ;
* Rastreabilidade das exclusões realizadas.

## 🛠️ Ajustes e Correções

#### Aplicativo DocZ para Android&#xD;

Atualizado, nos componentes do sistema, o link para disponibilização do aplicativo DocZ para Android.\
O novo link direciona para a versão do aplicativo que contempla a funcionalidade Fotolabel com Indexação Automática.

#### Salvamento dos Parâmetros do Projeto&#xD;

Corrigido o problema que impedia usuários com a permissão “Gerenciar Projetos dos Clientes” de salvar alterações nos Parâmetros do Projeto.\
A operação agora é concluída corretamente, garantindo que as configurações realizadas sejam mantidas no sistema.

#### Sincronização de Projetos no Cadastro de Usuários&#xD;

Ajustada a sincronização entre as Regras de Projeto e a aba Projetos do cadastro de usuários.\
Agora, os projetos aos quais o usuário possui acesso por meio das regras são refletidos corretamente em seu cadastro.

#### Nomenclatura no Dashboard de IA&#xD;

Atualizada a nomenclatura exibida no Dashboard de IA.\
O caminho anteriormente identificado como “Gestão de Guarda” passa a ser apresentado como “Gestão Documental”, mantendo a consistência com a estrutura atual do sistema.

#### Tratamento de Mensagem de Falta de Espaço de Armazenamento&#xD;

Implementado um tratamento específico para erros relacionados à falta de espaço de armazenamento durante a geração de relatórios.\
Nessas situações, o sistema passa a exibir uma mensagem mais clara, orientando o usuário sobre a indisponibilidade de espaço e a necessidade de entrar em contato com o suporte.

#### Histórico de Objetos&#xD;

Corrigido o comportamento que exibia um alerta indevido ao acessar o histórico de objetos sem registros.\
Agora, a janela de histórico é aberta normalmente, mesmo quando não houver informações registradas, evitando mensagens desnecessárias e melhorando a experiência de uso.

#### Notificação de Prazo de Guarda&#xD;

Corrigida a nomenclatura exibida no corpo dos e-mails relacionados ao monitoramento do prazo de guarda.\
O caminho informado passa a apresentar corretamente a funcionalidade Gestão Documental > Controle de Prazos e Destinações.

#### Configuração do Campo Classificação&#xD;

Corrigido o problema que impedia o salvamento da opção “Observação da Classe” na configuração do campo Classificação.\
A opção selecionada agora é mantida corretamente, evitando sua alteração indevida para “Identificador SOS” e possíveis impedimentos durante o processo de indexação.



🚀 Seguimos evoluindo o DocZ com foco em conformidade SBIS, segurança digital, rastreabilidade, integração e eficiência operacional.

{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Voltar</a>
