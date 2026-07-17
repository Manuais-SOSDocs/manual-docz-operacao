---
description: 'Versão: Docz v:2026.07.07.18.1.5.17.8'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 07/07/2026.

Nesta versão, o DocZ recebeu evoluções voltadas ao fortalecimento da gestão documental, atendimento de requisitos do e-ARQ Brasil, automação de processos operacionais e aprimoramento das configurações de integrações com sistemas externos.

A seguir, estão detalhadas as melhorias e correções disponibilizadas nesta versão.

### 📑 Melhorias e-ARQ Brasil

<details>

<summary><strong>🗃️ [E-ARQ] Configuração para selecionar Metadados que serão preservados ou excluídos após Expurgo de Documentos.</strong></summary>

Foi adicionada configuração por Projeto para definir quais metadados deverão permanecer armazenados no DocZ após a eliminação documental e quais serão automaticamente eliminados após a conclusão da O.S. de Expurgo. Todas as ações envolvidas no processo são registradas na trilha de auditoria.

🎯 Benefícios\
🔹 Preservação de informações essenciais após o expurgo\
🔹 Fortalecimento da auditoria, rastreabilidade e conformidade legal

</details>

<details>

<summary><strong>🗂️ [E-ARQ] Configuração para alteração automática da Etapa Documental após Expurgo</strong></summary>

Foi ampliada a parametrização das Ordens de Serviço de Expurgo (Eliminação), permitindo configurar a etapa documental que será atribuída aos documentos automaticamente após a conclusão da O.S.

🎯 Benefícios\
🔹 Maior automação do processo de eliminação documental

</details>

<details>

<summary><strong>⏳ [E-ARQ] Controle de Prazos e Destinações: Recálculo do Prazo de Guarda</strong></summary>

Foi disponibilizada uma nova funcionalidade para recalcular o prazo de guarda documental, permitindo alterar a classificação documental e/ou informar um prazo adicional de guarda. A data de destinação é recalculada automaticamente, mantendo a rastreabilidade das alterações realizadas.

🎯 Benefícios\
🔹 Mais flexibilidade na gestão do ciclo de vida documental\
🔹 Preservação da rastreabilidade e conformidade com o e-ARQ Brasil

</details>

<details>

<summary><strong>📑 [E-ARQ] Exportação Hierárquica da Tabela de Temporalidade</strong></summary>

A funcionalidade de exportação da Tabela de Temporalidade foi aprimorada para permitir exportações completas ou parciais, filtradas por um nível específico da estrutura hierárquica. Agora é possível selecionar uma Classe e, opcionalmente, uma Subclasse, exportando apenas os níveis hierárquicos vinculados.

🎯 Benefícios\
🔹 Mais flexibilidade na exportação das tabelas\
🔹 Redução da necessidade de exportações completas quando apenas parte da hierarquia é necessária

</details>

### 🔧 Melhorias Operacionais

<details>

<summary><strong>📄 Contabilização de Páginas Digitalizadas em Ordens de Serviço</strong></summary>

As Ordens de Serviço de Digitalização passam a contabilizar as páginas digitalizadas por item e por solicitação. O upload das imagens digitalizadas deve ser realizado a partir da tela de atendimento da O.S. O sistema contabiliza automaticamente e apresenta as informações nos relatórios vinculados às Ordens de Serviço.

🎯 Benefícios\
🔹 Apoio ao pré-faturamento\
🔹 Redução de divergências operacionais\
🔹 Maior rastreabilidade da produção realizada

</details>

<details>

<summary><strong>🔗 [GIP] Validação Inteligente da Localização em Integração via API</strong></summary>

Foi reforçada a validação do campo Localização durante a inclusão de arquivos em documentos (DC) por integração via API. O sistema passa a validar se a localização informada corresponde a uma caixa cadastrada, respeitando o padrão de nomenclatura, o código de guarda e as demais regras de consistência antes de permitir o preenchimento da Localização.

🎯 Benefícios\
🔹 Maior integridade dos dados integrados\
🔹 Redução de inconsistências cadastrais

</details>

<details>

<summary><strong>🔗 [GIP] Configuração de Upload via API por Documento</strong></summary>

Foi criada configuração por Projeto para controlar uploads via API, permitindo limitar o envio a um único arquivo por Documento e definir substituição automática quando aplicável. A configuração é aplicada exclusivamente às integrações via API, preservando o comportamento atual de inclusão de arquivos via interface do DocZ.

🎯 Benefícios\
🔹 Maior controle sobre integrações externas\
🔹 Flexibilidade para diferentes cenários de integração\
🔹 Redução de inconsistências por múltiplos arquivos enviados via API

</details>

<details>

<summary><strong>📑 [SBIS] Relatório de Conformidade de Assinaturas</strong></summary>

O Relatório de Conformidade de Assinaturas recebeu melhorias de layout e formatação para alinhamento ao modelo oficial de apresentação, incluindo atualização das informações de certificação SBIS e padronização visual do documento.

O relatório agora tem o número de identificação da certificação SBIS do DocZ.

🎯 Benefícios\
🔹 Apresentação mais padronizada do relatório\
🔹 Alinhamento às informações oficiais da certificação SBIS

</details>

### 🐞 Correções

<details>

<summary><strong>📄 Correção na geração do Relatório de Ordens de Serviço</strong></summary>

Foi corrigida inconsistência que impedia a geração do relatório em Excel para Ordens de Serviço com status "Em Atendimento".

🎯 Resultado\
🔹 O relatório passa a ser gerado corretamente para todos os status suportados pelo sistema.

</details>



🚀 Seguimos evoluindo o DocZ com foco em conformidade SBIS, segurança digital, rastreabilidade, integração e eficiência operacional.

{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Voltar</a>
