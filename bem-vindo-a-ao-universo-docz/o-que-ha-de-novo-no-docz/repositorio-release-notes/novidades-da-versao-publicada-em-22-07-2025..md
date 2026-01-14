---
description: 'Versão: Docz v:2025.07.22.19.4.9.6'
icon: bullhorn
---

# Novidades da Versão Publicada em 22/07/2025.

## Confira as últimas melhorias e correções implementadas no sistema DocZ.

### 🔐 Melhorias em Segurança e Gestão de Acessos

#### Novo Menu “Gestão de Usuários”

Agora, o DocZ tem um menu exclusivo para gerenciar acessos: “Gestão de Usuários”, com os subitens “Usuários” e “Grupos”.

* O menu “Configurações” passa a ser visível apenas para usuários com permissão de administrador.
* Usuários clientes não poderão visualizar nem editar grupos com o nome “SOS”, aumentando a confidencialidade e segurança interna.
* Bloqueio de criação de grupos com permissão de Administrador\
  A opção “Administrador” foi retirada da aba de permissões de grupos. Essa mudança previne atribuições indevidas de permissões críticas a grupos.

#### 🆎 Cadastro de Usuários com CPF Opcional

* Criado parâmetro para permitir o cadastro de usuários clientes sem a obrigatoriedade de CPF.
  * Quando ativado, o e-mail passa a ser o identificador único do usuário.
  * A plataforma valida e impede cadastros duplicados com o mesmo e-mail.

### 🛠️ Correções de Funcionalidade

#### Alterações em Metadados em Lote com Registro em Histórico

As alterações em metadados realizadas em lote (tanto em caixas quanto em documentos) agora salvam corretamente os logs no histórico de alterações.

#### Histórico de Chancela em Lote Corrigido

Ajustado o salvamento do histórico das chancelas aplicadas em lote, garantindo rastreabilidade completa das ações.



{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Retornar para anterior</a>
