---
description: 'Versão: Docz v:2026.05.28.18.1.5.17.6'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 28/05/2026.

## Confira as últimas melhorias e correções implementadas no sistema DocZ.

### 🚀 Novas Funcionalidades

<details>

<summary>📋 Espelhos Personalizados para Caixas</summary>

Foi disponibilizada uma nova funcionalidade que permite a criação e manutenção de Espelhos Personalizados diretamente pela interface do DocZ.\
Agora, usuários com as permissões adequadas podem configurar modelos de espelho para visualização e impressão de informações de caixas, utilizando campos e metadados já existentes no sistema.

🔧 Recursos disponíveis:\
🔹 Criação e edição de espelhos personalizados\
🔹 Seleção dos campos e metadados que compõem o espelho\
🔹 Configuração realizada integralmente pela interface do sistema\
🔹 Utilização por projeto conforme necessidade operacional\
🔹 Impressão das informações de documentos contidos nas caixas

🎯 Benefícios:\
🔹 Maior autonomia para usuários, gerentes e coordenadores de projetos\
🔹 Redução da dependência de desenvolvimento para criação de layouts e adaptação de campos\
🔹 Flexibilidade na apresentação das informações

</details>

<details>

<summary>📄 Configuração Dinâmica para Embarque de Metadados em PDF (Fase Inicial)</summary>

Foi implementada a primeira etapa da evolução do mecanismo de embarque de metadados em PDF no DocZ, introduzindo uma camada de configuração dinâmica por projeto.\
Nesta fase, passa a ser possível configurar regras e critérios que serão utilizados futuramente pelo sistema para definição dos metadados embarcados nos documentos PDF, utilizando chaves de decisão como tipologia documental, tipo documental, status e outros campos parametrizados do projeto.

🔧 Recursos disponíveis:\
🔹 Cadastro de regras específicas por projeto\
🔹 Configuração de chaves de decisão para seleção automática das regras\
🔹 Definição de regra padrão (default) para utilização quando não houver correspondência com regras específicas\
🔹 Estrutura preparada para suportar diferentes cenários documentais e requisitos de negócio\
🔹 Interface parametrizável para manutenção das regras sem necessidade de desenvolvimento

{% hint style="warning" %}
#### &#x20;Importante:&#xD;

Nesta etapa, a funcionalidade contempla a configuração das regras de embarque. A aplicação automática dessas configurações durante a geração dos PDFs será disponibilizada em versões futuras.
{% endhint %}

🎯 Benefícios:\
🔹 Maior flexibilidade na definição dos metadados documentais\
🔹 Redução de customizações específicas por cliente\
🔹 Preparação da plataforma para automação do embarque de metadados\
🔹 Maior aderência a requisitos de gestão documental e conformidade com o Decreto nº 10.278/2020

</details>

<details>

<summary>🔐 Autenticação por Certificado Digital</summary>

Foi implementado um novo método de autenticação que permite o acesso ao DocZ utilizando certificado digital.\
Durante o processo de login, o sistema realiza validações de identidade para garantir que o certificado utilizado pertença ao usuário cadastrado.

🔧 Recursos disponíveis:\
🔹 Login utilizando certificado digital\
🔹 Validação automática do CPF presente no certificado\
🔹 Conferência do CPF com o cadastro do usuário no DocZ\
🔹 Reforço dos mecanismos de autenticação e segurança

🎯 Benefícios:\
🔹 Maior segurança no acesso ao sistema\
🔹 Redução dos riscos de utilização indevida de credenciais\
🔹 Atendimento a requisitos de autenticação baseada em certificado digital

</details>

### 🔧 Melhorias

<details>

<summary>⏱️ Identificação de Carimbo de Tempo em Relatórios de Arquivos</summary>

O Relatório Analítico de Arquivos passou a disponibilizar uma nova coluna para identificação da existência de carimbo de tempo nos documentos.\
🔹 Nova coluna indicando a presença de carimbo de tempo\
🔹 Facilita auditorias e validações documentais\
🔹 Melhora a rastreabilidade das evidências de temporalidade

🗂️ Gestão Centralizada de Destinação Documental

A funcionalidade Controle de Prazos e Destinações foi ampliada para permitir o gerenciamento das destinações documentais com destinação final de Eliminação.\
Agora é possível acompanhar documentos com prazo de guarda cumprido e iniciar diretamente pelo sistema o processo de eliminação por meio da abertura de Ordens de Serviço de Expurgo.\
🔧 Recursos disponíveis:\
🔹 Monitoramento centralizado dos prazos de guarda\
🔹 Identificação de documentos aptos à destinação\
🔹 Abertura de OS de Expurgo diretamente pela tela

🎯 Benefícios:\
🔹 Maior conformidade com políticas de temporalidade\
🔹 Centralização dos processos de destinação\
🔹 Redução de atividades operacionais manuais

</details>

<details>

<summary>✍️ Evolução da Assinatura Digital com Integração Lacuna</summary>

Foi implementada a integração com os serviços de assinatura digital da Lacuna Software, ampliando os mecanismos de validação e segurança durante o processo de assinatura.\
🔧 Recursos disponíveis:\
🔹 Upload de certificado digital pelo usuário\
🔹 Validação da validade do certificado\
🔹 Verificação da cadeia certificadora (AC) configurada para o cliente\
🔹 Validação de revogação do certificado\
🔹 Assinatura em lote de arquivos da mesma DC\
🔹 Assinatura em lote de múltiplas DCs\
🔹 Parâmetros para personalização das validações obrigatórias por cliente

🎯 Benefícios:\
🔹 Maior segurança jurídica das assinaturas realizadas\
🔹 Flexibilidade para diferentes políticas de certificação\
🔹 Melhor experiência em operações de assinatura em massa

</details>

<details>

<summary>👥 Reorganização das Permissões de Usuários</summary>

Foi realizada uma reorganização estrutural das permissões de usuários do DocZ visando melhorar a navegação, administração e identificação dos acessos disponíveis.\
🔧 Ajustes realizados:\
🔹 Padronização das nomenclaturas das permissões\
🔹 Reorganização das permissões por contexto funcional\
🔹 Criação de agrupamentos específicos para Relatórios, Solicitações e Compartilhamento

🎯 Benefícios:\
🔹 Maior clareza na administração de usuários\
🔹 Facilidade na configuração de perfis\
🔹 Melhor organização das permissões do sistema

</details>

🚀 Seguimos evoluindo o DocZ com foco em conformidade SBIS, segurança digital, rastreabilidade, integração e eficiência operacional.



{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Voltar</a>
