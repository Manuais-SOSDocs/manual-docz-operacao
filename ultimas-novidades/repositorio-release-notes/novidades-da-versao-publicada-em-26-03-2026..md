---
description: 'Versão: Docz v:2026.03.26.18.1.5.16.1r'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 26/03/2026.

## Confira as últimas melhorias e correções implementadas no sistema DocZ.

{% hint style="info" %}
⚠️As melhorias desta versão são referentes às adequações e evoluções implementadas para atendimento ao processo de homologação do DocZ junto à SBIS (Sociedade Brasileira de Informática em Saúde).⚠️
{% endhint %}

## 🆕 Novas funcionalidades e melhorias

#### 1. Garantia de administrador ativo

Implementada regra de segurança para evitar a perda de acesso administrativo ao sistema.

🔹O sistema impede a inativação do último usuário com perfil de administrador\
🔹A ação só é permitida quando existir pelo menos outro administrador ativo\
🔹Exibição de mensagem orientando a necessidade de manter um administrador ativo

#### 2. Parametrização para alteração de objetos

Agora é possível configurar regras para alteração de objetos por meio de um novo parâmetro vinculado à etapa documental do projeto.

Regras aplicadas:\
🔹Quando a configuração estiver ativa, somente o usuário autor do objeto poderá alterar os metadados de objetos que estejam indexados na etapa documental definida na parametrização.\
🔹 O sistema passa a exigir justificativa obrigatória para qualquer alteração realizada.\
🔹Todas as alterações ficam registradas em uma nova aba na visualização do objeto, assegurando rastreabilidade e histórico das modificações.

#### 3. Inativação de arquivos

Foi incluído um novo parâmetro que permite configurar a inativação de arquivos conforme a etapa documental do projeto.

Comportamento: Usuários podem inativar arquivos quando estes estiverem na etapa configurada.

Arquivos inativos passam a exibir:

🔹 Marca d’água indicativa\
🔹 Identificação visual de status inativo

O sistema mantém histórico completo da inativação, incluindo:

🔹Justificativa\
🔹Usuário responsável\
🔹Data e hora da inativação

#### 4. Ajuste de Time Zone em relatórios

Os relatórios extraídos do sistema passam a considerar a configuração de fuso horário (time zone) definida no projeto, garantindo maior consistência das informações exibidas.

{% hint style="warning" %}
Importante: essa melhoria foi aplicada a todos os relatórios do sistema, tanto nos formatos Excel quanto PDF, assegurando padronização das datas e horários independentemente do tipo de exportação.
{% endhint %}

#### 5. Segurança na tela de login - Não persistência de credenciais

Foi implementada uma melhoria na tela de autenticação para usuários que acessam o DocZ por meio de usuário e senha.

Comportamento atualizado:

🔹 O sistema não memoriza nem sugere credenciais previamente utilizadas.\
🔹 Campos de login (Cliente, Usuário e Senha) passam a não exibir dados digitados em acessos anteriores.

{% hint style="info" icon="shield-keyhole" %}
Objetivo: aumentar a segurança no acesso ao sistema, evitando exposição indevida de credenciais em dispositivos compartilhados ou de uso público.
{% endhint %}

#### 6. Reforço de segurança no armazenamento de credenciais (melhoria técnica)

Foi implementada uma melhoria técnica no mecanismo de armazenamento e proteção de credenciais de autenticação dos usuários do DocZ.

Comportamento atualizado:

🔹As senhas passam a ser armazenadas utilizando hash criptográfico seguro (SHA-256), com tamanho mínimo de 160 bits.\
🔹Os parâmetros e dados de autenticação foram protegidos contra acessos não autorizados, seguindo boas práticas de segurança da informação.

{% hint style="info" icon="shield-keyhole" %}
Objetivo: reduzir o risco de vazamento de credenciais e garantir maior aderência a requisitos de segurança e conformidade.
{% endhint %}

#### 7.  Validação de CPF no upload de certificado de usuário

🧾Melhoria na consistência e segurança das informações.

🔹Validação do CPF conforme padrão oficial\
🔹Conferência com CPF do usuário logado\
🔹Bloqueio do upload em caso de divergência

#### 8. Download ZIP organizado por status

📦Melhoria na organização dos arquivos exportados.

🔹Separação automática em pastas: Ativos, Inativos e Deletados\
🔹Separação realizada automaticamente durante a geração do ZIP

### 🛠️ Correções e ajustes

#### 1. Correção de hiperlink na “Pasta Caixas”

Foi ajustado o comportamento na visualização da funcionalidade Pasta Caixas.

✔️ Agora: ao clicar no identificador SOS “Caixa”, o sistema direciona corretamente para a visualização da caixa, permitindo acesso aos documentos (DCs) vinculados.

#### 2. Correção no cadastro de usuários clientes

Ajustado problema que impedia o cadastro de usuários clientes no DocZ.

✔️ O fluxo de criação foi normalizado e está operando corretamente.

#### 3. Ajustes gerais de consistência e validação

Foram realizados ajustes internos para garantir maior estabilidade e consistência nas validações do sistema, incluindo:

🔹Tratamento de entradas inválidas em formulários\
🔹Melhorias na validação de permissões\
🔹Ajustes em fluxos de autenticação e auditoria

### 👥 Ajustes para Clientes:

#### 1. Espelho personalizado por cliente (COFFITO)

🧾Foi implementado Espelho Personalizado conforme necessidade do cliente.

#### 2. Falha ao salvar indexação de documentos (EMGEA / HMAB)

Corrigido comportamento que impedia o salvamento de documentos indexados

🔹Ajustado fluxo de persistência das DCs indexadas\
🔹Garantida a gravação correta dos dados após indexação

#### 3. Inconsistência de status “Arquivado” em caixas (DER-DF)

Corrigido comportamento de cancelamento de caixas.

🔹Mantido vínculo com status “Arquivado”\
🔹Liberadas novas solicitações para caixas armazenadas



{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Retornar para anterior</a>
