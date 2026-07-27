---
description: 'Versão: Docz v:2026.03.12.16.1.5.15.8'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 12/03/2026.

## Confira as últimas melhorias e correções implementadas no sistema DocZ.

### ✨ Melhorias

#### 🌍 Configuração de fuso horário por projeto (UTC)

Foi adicionada uma nova configuração no nível de projeto que permite parametrizar o fuso horário utilizando o padrão UTC (Coordinated Universal Time).

Essa melhoria garante maior padronização no registro de datas e horários do sistema, principalmente em ambientes com usuários distribuídos em diferentes regiões.

#### 🔐 Bloqueio de usuário por tentativas de login inválidas

Foi implementado um mecanismo de segurança para controle de tentativas de autenticação.

Regras aplicadas:

🔹 Após 5 tentativas consecutivas de login com credenciais incorretas, o usuário será automaticamente bloqueado.

🔹 O desbloqueio poderá ser realizado exclusivamente por um administrador do sistema.

Essa funcionalidade aumenta a segurança contra tentativas de acesso indevido.

#### 🗂️ Melhorias na funcionalidade “Calcular Prazo de Guarda”

Foram implementadas melhorias na funcionalidade Calcular Prazo de Guarda, com foco em facilitar a localização física dos documentos.

🔹Inclusão da coluna “Localização” na geração de todos os relatórios, permitindo identificar com mais facilidade onde os documentos da listagem gerada estão armazenados.

🔹Nova opção “Mostrar Endereço da Caixa”: foi adicionada uma checkbox que controla a exibição da coluna “Endereço” na grade de resultados da pesquisa.

* Quando a opção estiver habilitada, a coluna “Endereço” será exibida, apresentando o endereço da caixa onde o documento está armazenado.
* Quando estiver desativada, essa coluna não será exibida.<br>

#### 📄 Monitoramento de documentos com expurgo próximo

Foi criada uma nova área no sistema para monitoramento do prazo de guarda de registros.

Usuários com permissão específica poderão:

📌 Consultar documentos cujo prazo de guarda está próximo do vencimento.

📌 Monitorar registros com destinação final de Eliminação ou Guarda permanente.

O objetivo é facilitar a gestão do ciclo de vida documental e apoiar ações preventivas antes do vencimento dos prazos.

#### 🧾 Informações de versão do software no rodapé das páginas

Foram adicionadas novas informações de versão do software no rodapé das páginas do sistema.

Com isso, passa a ser possível identificar com mais facilidade:

🔹 Versão do sistema em execução

🔹 Informações úteis para suporte e diagnóstico

{% hint style="warning" icon="screwdriver-wrench" %}
### Correções

**🧩 Exibição de “NULL” em campos vazios**

Corrigido comportamento que exibida o valor “NULL” na visualização de versões de objetos. Campos sem informação agora são exibidos em branco, melhorando a clareza da interface.
{% endhint %}





{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Retornar para anterior</a>
