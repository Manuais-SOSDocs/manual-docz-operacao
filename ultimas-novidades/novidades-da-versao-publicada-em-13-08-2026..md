---
description: 'Versão: Docz v:2026.08.13.18.1.5.17.11'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 13/08/2026.

Nesta versão, o DocZ recebeu novas funcionalidades e melhorias na gestão de Ordens de Serviço, nas integrações via API, na geração de relatórios e no controle de permissões, além de correções em diferentes fluxos do sistema.

## 📦 Novas Funcionalidades

#### 📄 Impressão de Ordens de Serviço em Lote

Foi disponibilizada a funcionalidade de Impressão em Lote, que permite gerar relatórios de múltiplas Ordens de Serviço a partir dos resultados apresentados na tela de Solicitações.

_ℹ️ Cada lote pode conter até 20 Ordens de Serviço._

O usuário pode selecionar as OS desejadas e escolher entre as seguintes opções:

* Imprimir Localização Grid;
* Imprimir Localização;
* Imprimir OS.

O processamento ocorre em segundo plano. Ao término, os arquivos são agrupados em um único arquivo .zip, disponibilizado na Central de Downloads. O usuário também recebe uma notificação por e-mail quando o processamento é concluído.

Cada OS incluída na exportação gera um registro específico na Trilha de Auditoria, com a identificação do tipo de relatório emitido.

_Benefícios: redução do trabalho operacional, maior agilidade na emissão de documentos, processamento assíncrono e centralização dos arquivos gerados._

#### 🔗 Registro de Operações de APIs na Trilha de Auditoria

As operações realizadas por meio das APIs DocZ Integra, FileService e FileUtils passaram a ser registradas na Trilha de Auditoria.

Os registros seguem o mesmo padrão de rastreabilidade adotado para as ações realizadas pela interface do DocZ, permitindo identificar as operações executadas por integrações e serviços.

Benefícios: maior rastreabilidade das operações automatizadas, identificação da origem das ações, fortalecimento dos controles de auditoria e maior aderência aos requisitos de governança e rastreabilidade do SIGAD.

#### 🏢 Origem na OS de Saída Definitiva

Foi incluído o campo Origem na criação das Ordens de Serviço do tipo Saída Definitiva.

O campo é opcional e apresentado como uma lista suspensa contendo os galpões vinculados ao respectivo projeto. Quando preenchido, o galpão selecionado passa a ser apresentado como Unidade de Atendimento na OS.

_Benefícios: registro mais preciso da unidade de origem, redução de etapas manuais e melhoria da rastreabilidade das movimentações documentais._

## 🛠️ Ajustes e Correções

#### 📝 Observações no Relatório de OS em PDF

O relatório de Ordem de Serviço em PDF foi aprimorado para apresentar o conteúdo registrado na aba Observações durante a abertura da solicitação.\
As informações são recuperadas automaticamente e apresentadas junto aos dados gerais da OS, antes dos itens da solicitação, preservando o texto registrado pelo usuário.

_Benefícios: maior completude dos relatórios, preservação das informações registradas durante a solicitação e facilidade para consulta._

#### 🩺 Configuração do serviço de conversão via interface

Foram implementadas melhorias no monitoramento dos serviços responsáveis pelo processo de conversão documental.

No fluxo de conversão, foram aprimoradas as validações relacionadas à necessidade de processamento e ao tamanho dos arquivos gerados. Também passou a ser possível parametrizar, via interface nas configurações do Projeto, as etapas de entrada e saída da conversão.

_Benefícios: mais flexibilidade na configuração, maior visibilidade operacional, redução de processamentos desnecessários, controle do tamanho dos arquivos e redução de impactos sobre o armazenamento._

#### 🔐 Herança de Permissões de Grupos

Foi ajustado o mecanismo de aplicação das permissões atribuídas aos grupos de usuários.\
Agora, as permissões configuradas para um grupo são herdadas corretamente pelos usuários vinculados a ele, garantindo a aplicação efetiva dos acessos definidos pela administração.

_Benefícios: maior consistência no controle de acesso, redução de configurações manuais individuais e maior confiabilidade na administração das permissões._

#### 📦 Inserção de Documentos em Caixas

Foi corrigida a falha apresentada durante a indexação por formulário ao informar o endereço de uma caixa para vinculação de documentos.

Com a correção, o processo de indexação pode ser concluído normalmente, associando o documento à caixa informada.

#### 📧 Envio de E-mails após a Conclusão da Indexação

Foi corrigido o fluxo de notificações associado à conclusão das etapas de indexação.\
Agora, após a alteração do status da etapa para Concluído, os e-mails de notificação são enviados aos endereços cadastrados para o recebimento desses comunicados.

#### 🔄 Correção na Duplicação de Ordens de Serviço

Foi corrigida a falha que poderia ocasionar a criação duplicada de Ordens de Serviço, com a repetição da numeração das caixas.

O fluxo foi ajustado para impedir a geração de registros duplicados e preservar a consistência das informações vinculadas às OS.



🚀 Seguimos evoluindo o DocZ com foco em conformidade SBIS, segurança digital, rastreabilidade, integração e eficiência operacional.

{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
