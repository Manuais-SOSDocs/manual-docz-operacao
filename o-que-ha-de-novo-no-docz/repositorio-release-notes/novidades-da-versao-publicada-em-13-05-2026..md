---
description: 'Versão: Docz v:2026.05.13.22.1.5.17.4'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 13/05/2026.

## Confira as últimas melhorias e correções implementadas no sistema DocZ.

### 🚀 Novas Funcionalidades

<details>

<summary>🕓 Reclassificação Automática de Documentos</summary>

Foi implementado um novo mecanismo de reclassificação automática de documentos a partir da edição de códigos da Tabela de Temporalidade no DocZ.

Agora, qualquer alteração realizada em um código da Tabela de Temporalidade pode ser automaticamente aplicada aos documentos classificados naquele código, mediante confirmação do usuário. A atualização dos metadados ocorre em background e gera automaticamente uma nova versão do objeto, garantindo maior rastreabilidade, auditoria e conformidade com os requisitos de gestão documental.

🔧 Recursos disponíveis:&#x20;

🔹 Aplicação automática das alterações da Tabela de Temporalidade aos documentos vinculados ao código alterado \
🔹 Registro automático das alterações como nova versão do objeto \
🔹 Exibição das alterações na aba “Versões” da View Object \
🔹 Identificação dos campos alterados \
🔹 Registro de data e histórico das alterações realizadas \
🔹 Maior rastreabilidade das modificações executadas em background

🎯 Benefícios:&#x20;

🔹 Maior aderência aos requisitos do e-ARQ Brasil \
🔹 Transparência nas alterações realizadas automaticamente pelo sistema \
🔹 Redução de atividades manuais de reclassificação documental

</details>

<details>

<summary>🔔 Central de Notificações do Sistema</summary>

Foi implementada a nova Central de Notificações do DocZ, permitindo que usuários acompanhem avisos, alertas operacionais e comunicados importantes diretamente na plataforma.

A funcionalidade disponibiliza um ícone de notificações 🔔 na barra superior do sistema, indicando quando existirem novos eventos ou notificações pendentes para visualização.

🔧 Recursos disponíveis:&#x20;

🔹 Ícone de notificações com indicação visual de novos avisos \
🔹 Centralização de comunicados e eventos importantes do sistema, de acordo com as permissões do usuário logado \
🔹 Visualização de notificações operacionais e institucionais \
🔹 Acompanhamento facilitado de pendências e atualizações relevantes

🎯 Benefícios:&#x20;

🔹 Comunicação centralizada no sistema \
🔹 Melhor acompanhamento das atividades e pendências do usuário

</details>

### ⚙️ Ajustes

<details>

<summary>📈 Inclusão da Data de Finalização no Relatório de Ordens de Serviço</summary>

Foi realizado um ajuste no relatório de Ordens de Serviço exportado em Excel, disponível na funcionalidade de Consulta de Solicitações.

🔧 Ajustes realizados:&#x20;

🔹 Inclusão da coluna “Data de Finalização” no relatório exportado \
🔹 Ampliação das informações disponíveis para análises operacionais e gerenciais

🎯 Benefícios:&#x20;

🔹 Melhor acompanhamento do ciclo de atendimento das solicitações \
🔹 Maior visibilidade sobre prazos e eficiência operacional \
🔹 Facilitação da análise de desempenho e identificação de gargalos

</details>

<details>

<summary>🏢 Inclusão de Novo Endereçamento no EtqPress — Galpão SIA G5</summary>

Foi realizada a inclusão das novas alturas de endereçamento no sistema EtqPress para atendimento das necessidades operacionais do galpão SIA G5.

🔧 Ajustes realizados:&#x20;

🔹 Inclusão das alturas 13 e 14 no endereçamento do galpão \
🔹 Adequação da estrutura para continuidade do processo de auditoria do acervo

</details>

<details>

<summary>🔗 Ajuste de Redirecionamento de Documentos na Integração SGE x DocZ</summary>

Foi realizado ajuste no comportamento da integração do DocZ com o SGE para visualização de documentos do DocZ via SGE.

🔧 Ajuste realizado:&#x20;

🔹 Correção do redirecionamento indevido para tela inicial/login \
🔹 Adequação da abertura direta do documento para usuários autenticados no SGE

🎯 Benefícios:&#x20;

🔹 Melhor experiência de navegação integrada \
🔹 Continuidade do fluxo operacional de matrícula e conferência documental \
🔹 Redução de interrupções no processo de validação de documentos

</details>

### 🔧 Correções

<details>

<summary>🔐 Correção da Política de Assinatura Digital AD-RT</summary>

Foi realizada a correção da identificação do carimbo de tempo nas assinaturas digitais geradas pelo sistema.

🔧 Ajuste realizado:&#x20;

🔹 Correção da indicação incorreta do carimbo de tempo como “ADRB” \
🔹 Ajuste do arquivo relacionado ao carimbo de tempo: PA\_AD\_RB\_v2\_3.der

{% hint style="info" icon="thumbtack-angle" %}
A correção garante aderência ao requisito NGS2.04.01, assegurando que as assinaturas digitais geradas pelo S-RES sigam, no mínimo, a política AD-RT (Assinatura Digital com Referências de Tempo), incluindo os objetos necessários à validação da assinatura.
{% endhint %}

</details>

<details>

<summary>📊 Correção de Filtros de Datas em Relatórios</summary>

Foi realizada a correção do comportamento dos filtros relacionados às opções de “Data de Inventário” e “Data de Cat. Complementar” nos relatórios do sistema.

🔧 Correções realizadas:&#x20;

🔹 Ajuste na exportação considerando corretamente os filtros específicos de data \
🔹 Correção da interpretação das ações de inventário e indexação \
🔹 Maior precisão na identificação das operações realizadas nos períodos selecionados

</details>

<details>

<summary>📄 Correção na Visualização de Ordens de Serviço</summary>

Foi corrigido um problema que impedia a abertura e visualização de Ordens de Serviço em determinados ambientes/clientes.

🔧 Correção realizada:&#x20;

🔹 Ajuste no carregamento e exibição das Ordens de Serviço \
🔹 Correção aplicada para os cenários identificados nos clientes Anchieta e BRB

</details>

🚀 Seguimos evoluindo o DocZ com foco em segurança, rastreabilidade, integração e eficiência operacional.



{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Retornar para anterior</a>
