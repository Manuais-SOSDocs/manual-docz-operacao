---
description: 'Versão: DocZ v:2026.02.26.17.1.5.15.5'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 26/02/2026.

## Confira as últimas melhorias e correções implementadas no sistema DocZ.

{% hint style="warning" %}
#### Contexto da Versão

As melhorias desta versão são referentes às adequações e evoluções implementadas para atendimento ao processo de homologação do DocZ junto à SBIS (Sociedade Brasileira de Informática em Saúde).
{% endhint %}

### 🚀 MELHORIAS

#### 🔐 1. Termos de Uso – Aceite Obrigatório

Implementado fluxo de aceite obrigatório dos Termos de Uso:

* Exibido no primeiro acesso de novos usuários
* Exibido sempre que houver atualização do termo vigente
* O Acesso ao sistema é liberado somente após o aceite formal

A medida fortalece a conformidade jurídica e formaliza a ciência do usuário quanto às regras de utilização da plataforma.

#### 🛡️ 2. Reforço de Auditoria – Ações Críticas de Segurança

Revisão e ampliação do registro de ações críticas relacionadas a:

* Autenticação
* Segurança
* Gestão de usuários

As ações passam a ser registradas com maior nível de detalhamento na Trilha de Auditoria, garantindo maior rastreabilidade, melhor governança, elevação do nível de segurança operacional

#### 🆔 3. Inclusão do ID do Usuário na Trilha de Auditoria

A Trilha de Auditoria passa a registrar também o ID interno do usuário responsável pela ação.

A melhoria elimina ambiguidades em casos de usuários com nomes semelhantes e aumenta a precisão das análises técnicas e auditorias.

#### 🔒 4. Bloqueio Total em Cenários de Troca Obrigatória de Senha

Implementado fluxo de segurança que bloqueia totalmente a navegação sempre que houver exigência de troca obrigatória de senha.

📌 Cenários aplicáveis:

* Primeiro acesso do usuário
* Senha vencida após 90 dias
* Recuperação de senha realizada na tela de login
* Geração de nova senha por usuário com perfil autorizado

🔐 Comportamento do sistema:

* A navegação é integralmente bloqueada
* Apenas a tela de redefinição de senha permanece acessível
* Nenhuma funcionalidade pode ser utilizada até a conclusão bem-sucedida da alteração

A medida elimina riscos associados ao uso de senha provisória ou expirada e reforça a política de segurança da informação, garantindo conformidade com boas práticas de controle de acesso.<br>

### 🛠️ CORREÇÕES

#### 5. Correção – Salvamento de Metadados

Corrigido o comportamento de salvamento de alterações de metadados nos seguintes pontos:

* Aba “Versões” do objeto
* Botão de Log na tela de pesquisa

A correção garante persistência adequada das alterações realizadas e maior consistência das informações exibidas.

#### 6. Correção de Comportamento – Tipo de Vínculo no Cadastro de Usuário

Corrigido o comportamento que permitia a criação de usuário sem definição do tipo de vínculo.

Agora, a seleção de Cliente ou SOS é obrigatória para conclusão do cadastro.\
Caso não seja selecionada uma das opções, o sistema bloqueia o salvamento e exibe mensagem de validação.



{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Retornar para anterior</a>
