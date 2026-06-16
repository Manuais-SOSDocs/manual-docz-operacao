---
description: 'Versão: Docz v:2026.05.04.16.1.5.17.3'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 05/05/2026.

## Confira as últimas melhorias e correções implementadas no sistema DocZ.

### 🚀 Novas Funcionalidades

<details>

<summary>📝Seleção Dinâmica de Pasta de Destino na Indexação</summary>

Foi implementada a possibilidade de definir dinamicamente a pasta de destino durante o processo de indexação, trazendo mais flexibilidade e eficiência na organização documental.

⚠️ A funcionalidade depende de ativação via parâmetro no formulário de indexação.

**🔧 Recursos disponíveis:**

🔹 Campo “Pasta de destino” exibido no formulário de indexação\
🔹 Seleção de qualquer pasta ou subpasta da estrutura\
🔹 Pesquisa por nome de pasta\
🔹 Fixação da pasta selecionada durante a sessão de indexação do usuário\
🔹 Limpeza da seleção via ação explícita

**⚙️ Como funciona na prática?**

🔹 Documento é salvo diretamente na pasta selecionada no momento da indexação\
🔹 Caso não haja seleção, o sistema utiliza automaticamente a pasta padrão do formulário\
🔹 A pasta final é registrada nos metadados do documento, garantindo rastreabilidade

**💡 Benefícios da funcionalidade:**

<table data-card-size="large" data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><strong>🎯 1. Simplificação da estrutura de formulários</strong></p><p>Permite a criação de um único formulário centralizado (ex: pasta raiz “DOCUMENTOS”), eliminando a necessidade de múltiplos formulários distribuídos por pasta.</p><p>➡️ Reduz complexidade de configuração<br>➡️ Facilita manutenção e evolução do sistema</p></td></tr><tr><td><p><strong>🚀 2. Ganho de produtividade operacional</strong></p><p>Evita etapas adicionais de movimentação manual de documentos após a indexação.</p><p>➡️ Flexibilidade na organização documental<br>➡️ Processo mais ágil e direto</p></td></tr><tr><td><p><strong>🧭 3. Movimentação lógica via formulário</strong></p><p>O próprio formulário passa a atuar como ponto de decisão da localização do documento, permitindo alteração/movimentação da pasta já no momento da indexação.</p><p>➡️ Centraliza a ação no fluxo principal<br>➡️ Reduz dependência de funcionalidades posteriores</p></td></tr><tr><td><p><strong>🧩 4. Escalabilidade da solução</strong></p><p>Com um modelo desacoplado de formulários por pasta, o sistema se torna mais preparado para crescimento da estrutura organizacional.</p><p>➡️ Facilita expansão de pastas/subpastas<br>➡️ Evita reconfigurações estruturais frequentes</p></td></tr></tbody></table>

</details>

<details>

<summary>🗃️ Alerta de Limiar de Ocupação de Armazenamento</summary>

Foi implementado o controle de capacidade de armazenamento por cliente, com envio automático de alertas quando o limite configurado for atingido.

⚠️ A funcionalidade depende de ativação por parâmetro configurado por cliente.

Recursos disponíveis:\
🔹 Configuração de limite de armazenamento por cliente (em GB)\
🔹 Definição de limiar percentual para disparo de alerta\
🔹 Envio automático de notificações por e-mail cadastrado\
🔹 Monitoramento contínuo da ocupação

</details>

### ⚙️ Melhorias

<details>

<summary>1. Filtro por Tipo de Data em Relatórios de OS</summary>

Adicionamos o filtro "Tipo de Data" no módulo de Solicitações para a emissão de relatórios de Ordens de Serviço. Essa novidade permite definir o período de busca com maior precisão, facilitando a análise operacional e atendendo melhor às demandas de faturamento.

🔹 Novas opções de filtro disponíveis:

* Data de Abertura
* Data de Atendimento
* Data de Finalização

</details>

<details>

<summary>2. Inclusão do Status de Transporte no Relatório Analítico de OS</summary>

O relatório analítico passou a exibir o status do transporte vinculado à OS.

🔹 Nova coluna: “Status do Transporte”\
🔹 Exibição consistente com módulo de transporte\
🔹 Valor “Sem Transporte” quando não houver vínculo

</details>

<details>

<summary>3. Rastreabilidade de Ações de Transporte na OS</summary>

As ações realizadas no transporte agora são refletidas no histórico da OS vinculada.

🔹 Registro automático de eventos como:

* Transporte iniciado
* Atrasado
* Finalizado
* Cancelado

</details>

<details>

<summary>4. Aprimoramentos na Central de Downloads</summary>

🔹 E-mail de Falha de Processamento Caso o sistema encontre um erro ao gerar relatórios (Padrão, Ações de Usuário, Cliente ou Indexação) e não consiga enviá-los para a Central de Downloads, o usuário receberá imediatamente um e-mail de alerta informando a falha, com a data e hora da tentativa, orientando-o a tentar novamente ou contatar o suporte.

🔹 Coluna "Tamanho do Arquivo" A grid da Central de Downloads passará a exibir o tamanho de cada arquivo disponível. A nova coluna ficará posicionada entre as colunas "Status do Relatório" e "Arquivo para Download".

</details>

<details>

<summary>5. Ajustes no Relatório de Storage</summary>

Foram realizados aprimoramentos no relatório de storage, com inclusão de novas métricas e reorganização da interface para melhor análise do consumo de armazenamento.

**Como funciona na prática?**

🔹 O cálculo de ocupação passa a considerar o repositório físico (disco), refletindo o uso real de armazenamento\
🔹 As informações são apresentadas de forma segmentada para facilitar a análise por tipo de dado

Informações disponíveis:

🔹Quantidade de Arquivos

🔹Volume de Imagens

🔹Ocupação do Repositório (GB)

</details>

<details>

<summary>6. Atualização de Dados na API</summary>

Visando melhorar a governança e a padronização da documentação técnica os dados de contato na  API FileService e FileUtils.

🔹 Substituição de informações individuais por dados institucionais

</details>

<details>

<summary>7. Ajuste em PDF Assinado por Automação</summary>

Atualizado o nome da aplicação exibido nos metadados das propriedades do PDF .

✅ Nome do "assinador" atualizado: SOS Tecnologia e Gestão da Informação

</details>

### 🛠 Correções

<details>

<summary>1. Tabela de Temporalidade</summary>

Corrigidos problemas na criação e exclusão de registros.

❌ Antes:

* Mensagens de erro mesmo com sucesso
* Registros duplicados

✅ Agora:

* Mensagens corretas de sucesso
* Eliminação de duplicidade

</details>

<details>

<summary>2. Finalização de Ordens de Serviço</summary>

Corrigida lentidão na finalização de OS.

❌ Antes: processamento demorado e instável\
✅ Agora: finalização com comportamento estável

</details>

<details>

<summary>3. Formulário de Indexação via IA</summary>

Corrigido erro em campos de data.

❌ Antes: loop infinito ao preencher data\
✅ Agora: salvamento normal do formulário

</details>

🚀 Seguimos evoluindo o DocZ com foco em conformidade SBIS, segurança digital, rastreabilidade, integração e eficiência operacional.



{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Voltar</a>
