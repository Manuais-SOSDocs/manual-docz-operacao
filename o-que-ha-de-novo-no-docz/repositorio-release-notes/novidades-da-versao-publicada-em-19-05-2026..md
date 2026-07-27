---
description: 'Versão: Docz v:2026.05.19.17.1.5.17.5'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 19/05/2026.

## Confira as últimas melhorias e correções implementadas no sistema DocZ.

{% hint style="info" icon="diamond-exclamation" %}
As melhorias desta versão são referentes às adequações e evoluções implementadas para atendimento ao processo de homologação do DocZ junto à SBIS (Sociedade Brasileira de Informática em Saúde).
{% endhint %}

### 🚀 Novas Funcionalidades

<details>

<summary>🔐 Validação de Assinaturas Digitais no DocZ</summary>

Foi implementada no DocZ a funcionalidade de validação de assinaturas digitais diretamente pela aba Arquivos dos documentos, permitindo que usuários realizem a conferência das assinaturas sem necessidade de download do arquivo ou utilização de ferramentas externas.

A validação é executada por integração com o motor de validação da Lacuna Software e pode ser acessada diretamente pelo ícone do Histórico de Assinaturas. Além da validação em tela, o sistema também passou a disponibilizar a emissão sob demanda do Relatório PDF de Validação de Assinaturas, gerado em tempo real mediante nova validação automática das assinaturas no momento da emissão.

Durante o processo, o DocZ realiza verificações completas relacionadas à integridade do conteúdo assinado, validade do certificado digital do signatário, cadeia de certificação, situação de revogação do certificado e validação de carimbo de tempo, quando aplicável. O sistema também suporta arquivos com múltiplas assinaturas, consolidando automaticamente os resultados e apresentando o detalhamento individual de cada assinatura validada.

O resultado da validação passou a ser exibido de forma detalhada dentro do próprio sistema, incluindo:

* status individual das assinaturas;
* análise de integridade do documento;
* identificação das causas de assinaturas inválidas ou indeterminadas;
* resumo quantitativo das assinaturas analisadas;
* relatório de conformidade retornado pelo validador;
* indicador visual de processamento durante a validação.

Para essa funcionalidade, foram disponibilizados novos recursos no modal Histórico de Assinaturas:

* botão “Validar Assinaturas”;
* botão “Baixar Relatório PDF”;
* possibilidade de revalidação sob demanda pelo usuário;
* emissão dinâmica do PDF sem persistência no acervo documental;
* inclusão da mensagem legal ICP-Brasil/SBIS no relatório.

Os estados de validação apresentados pelo sistema incluem:

* Assinatura Válida;
* Assinatura Inválida;
* Assinatura Indeterminada.

#### 🎯 Benefícios

🔹 Maior confiabilidade na validação de documentos assinados digitalmente\
🔹 Redução da necessidade de ferramentas externas de conferência\
🔹 Maior rastreabilidade e segurança jurídica dos documentos\
🔹 Cumprimento de requisitos de conformidade SBIS\
🔹 Maior transparência no processo de validação digital\
🔹 Facilidade na identificação de inconsistências e falhas de assinatura\
🔹 Melhoria na auditoria e análise de conformidade documental\
🔹 Apoio operacional para validações jurídicas e administrativas\
🔹 Disponibilização de evidência formal de validação de assinaturas digitais.

</details>

<details>

<summary>🔌 Novos Endpoints de Consulta de Solicitações no DocZ Integra (API)</summary>

Foram disponibilizados novos endpoints no DocZ Integra para consulta de solicitações do módulo de Solicitações do DocZ, permitindo integrações mais robustas e parametrizáveis.

🔧 Recursos disponíveis:

🔹 Consulta por Tipo de Solicitação; Prioridade da Solicitação; Status SLA; Tipo de Solicitante; Tipo de Data; Intervalo de datas; Número da solicitação; Número de Etiqueta SOS vinculada; Consulta por Número de Etiqueta SOS vinculada

🎯 Benefícios:

🔹 Maior flexibilidade para integrações externas\
🔹 Recuperação eficiente de solicitações por critérios de negócio\
🔹 Padronização das consultas via API\
🔹 Ampliação das possibilidades de automação operacional

</details>

### ✨Melhorias

<details>

<summary>🛡️ Ampliação da Trilha de Auditoria para Assinaturas Digitais</summary>

Foi ampliada a trilha de auditoria do DocZ para contemplar eventos relacionados à validação de assinaturas digitais.

🔧 Ajustes realizados:

🔹 Registro de eventos de validação de assinatura digital\
🔹 Registro de falhas na validação de assinatura digital\
🔹 Registro de revalidação para emissão de relatório\
🔹 Registro de geração de relatório de assinaturas\
🔹 Registro de download do relatório de assinaturas\
🔹 Inclusão de detalhamento técnico de falhas no campo Observações\
🔹 Registro de usuário executor, data/hora e objeto afetado

🎯 Benefícios:

🔹 Maior rastreabilidade das operações de validação\
🔹 Fortalecimento da trilha de auditoria e governança documental\
🔹 Apoio a auditorias de segurança e conformidade

</details>

<details>

<summary>🔐 Validação de Certificados Antes da Assinatura Digital</summary>

Foi implementada validação prévia dos atributos obrigatórios do certificado digital antes da realização da assinatura.

🔧 Ajustes realizados:

🔹 Validação do campo Key Usage do certificado digital\
🔹 Verificação obrigatória dos atributos:

* Digital Signature
* Non Repudiation / Content Commitment

🔹 Bloqueio da assinatura para certificados incompatíveis\
🔹 Exibição de mensagem informativa ao usuário em caso de incompatibilidade\
🔹 Registro da ocorrência na trilha de auditoria

🎯 Benefícios:

🔹 Prevenção de assinaturas incompatíveis ou inválidas\
🔹 Maior conformidade com padrões ICP-Brasil\
🔹 Redução de falhas operacionais no processo de assinatura digital

</details>

### ⚙️ Ajustes

<details>

<summary>🔔 Ajustes na Central de Notificações</summary>

Foram realizados ajustes na Central de Notificações relacionados à exibição das Release Notes.

🔧 Ajustes realizados:

🔹 Correção da exibição do título da release\
🔹 Correção da exibição da data da última release publicada\
🔹 Alinhamento entre os dados cadastrados e os dados apresentados ao usuário

🎯 Benefícios:

🔹 Melhor experiência de navegação e consulta das releases\
🔹 Maior consistência das informações apresentadas ao usuário

</details>

🚀 Seguimos evoluindo o DocZ com foco em conformidade SBIS, segurança digital, rastreabilidade, integração e eficiência operacional.



{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Voltar</a>
