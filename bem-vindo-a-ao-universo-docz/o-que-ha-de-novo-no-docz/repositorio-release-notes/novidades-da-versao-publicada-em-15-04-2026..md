---
description: 'Versão: Docz v:2026.04.15.20.1.5.17.2'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 15/04/2026.

## Confira as últimas melhorias e correções implementadas no sistema DocZ.

### 🚀 Novas Funcionalidades

<details>

<summary>1. Notificação de Prazo de Guarda por E-mail [e-ARQ 3.1.3]</summary>

Foi implementado um mecanismo automático de alerta para documentos próximos de atingir o prazo de guarda definido na Tabela de Temporalidade.

⚠️ A funcionalidade deve ser configurada por projeto por meio de parâmetro específico.

Após a ativação, o sistema passa a enviar notificações quando forem identificados objetos próximos do vencimento.

Recursos disponíveis:\
🔹 Envio automático de notificações por e-mail aos destinatários cadastrados\
🔹 Possibilidade de alerta dentro do próprio sistema\
🔹 Registro de todos os envios na trilha de auditoria 📩

O objetivo é permitir que usuários responsáveis avaliem os documentos e iniciem ações de destinação antes do vencimento, garantindo conformidade com as práticas de gestão documental.

</details>

<details>

<summary>2. Ações de Destinação no Monitoramento de Prazo de Guarda [e-ARQ 3.1.4]</summary>

A tela de Monitoramento de Prazo de Guarda passou a permitir a abertura direta do processo de destinação documental.

Ações disponíveis:\
🔹 Eliminação de documentos\
🔹 Recolhimento para guarda permanente\
🔹 Recalcular prazo de guarda

As ações:\
🔸 Exigem confirmação prévia\
🔸 São registradas como pendentes de aprovação\
🔸 Ficam registradas em log de auditoria

Para documentos com nível de sigilo, o sistema exibe um aviso adicional antes da confirmação.

A execução final da destinação deve ser configurada de acordo com o fluxo de integrações do cliente.

</details>

### ⚙️ Melhorias

<details>

<summary>1. Relatório de Arquivos – Identificação de Assinaturas</summary>

Os relatórios de arquivos foram aprimorados para evidenciar a presença de assinaturas digitais.

🔹 Relatório Simples: nova coluna _“Possui Assinatura?”_\
🔹 Relatório Analítico: inclusão de informações detalhadas:

* Ação realizada
* Tipo de assinatura
* Usuário responsável
* Data e hora

As informações são obtidas diretamente do histórico de assinaturas, reforçando rastreabilidade e suporte a auditorias. 🔎

</details>

<details>

<summary>2. Indexação via API – Validação de Etiquetas de Caixas Físicas</summary>

Corrigido comportamento no endpoint:\
POST /api/v1/objetos/indexacao

❌ Antes: etiquetas válidas eram rejeitadas com erro “Etiqueta com caracteres inválidos”\
✅ Agora: validação ajustada para aceitar corretamente etiquetas de caixas físicas (CX e CB), incluindo variações de siglas

</details>

<details>

<summary>3. Monitoramento de Prazo de Guarda</summary>

Aprimoramentos realizados na funcionalidade:

🔹 Correção da exibição da Classificação no formato Código | Assunto\
🔹 Padronização de exibição em filtros e grid\
🔹 Correção da lógica dos filtros:

* Prazo vencido
* A vencer no ano corrente
* Ajuste no filtro por Identificador SOS
* Marcação adequada de campos obrigatórios

</details>

<details>

<summary>4. Ajustes em ações registradas na Trilha de Auditoria</summary>

Para ações de assinaturas de arquivos, a coluna Objeto agora apresenta o padrão:\
🔹 ID SOS – Nome do arquivo

Facilitando a identificação do item relacionado à operação registrada.

</details>

<details>

<summary>5. Envio de Senha após Desbloqueio de Usuário</summary>

Corrigido fluxo onde o sistema não enviava nova senha após desbloqueio realizado por administrador.

📩 Agora o envio é feito automaticamente após o desbloqueio.

</details>

<details>

<summary>6. Ajuste em Espelho Personalizado do cliente NOVACAP</summary>

Corrigido problema na geração de espelhos personalizados onde o metadado “Data da Criação” era exibido em branco.

✅ Agora o campo é preenchido corretamente quando indexado.

</details>

<details>

<summary>7. Ajustes em mensagens de retorno – Inclusão de Comentários via API</summary>

Realizada a padronização das mensagens de retorno na operação de inclusão de comentários em objetos via API.

❌ Antes: respostas inconsistentes, podendo retornar códigos inadequados mesmo quando o comentário era criado com sucesso\
✅ Agora: retornos alinhados ao resultado da operação, utilizando códigos HTTP apropriados para sucesso (como 200 ou 201)

Essa melhoria aumenta a confiabilidade no consumo da API e facilita o tratamento das respostas por sistemas integrados com o DocZ.

</details>

### 🛠 Correções

<details>

<summary>1. Exclusão de Veículos Vinculados</summary>

Corrigido comportamento em que o sistema informava sucesso ao excluir veículos com vínculos ativos, sem efetivar a exclusão.

✅ Agora o sistema:\
🔹 Impede a exclusão\
🔹 Exibe mensagem informando a existência de vínculos

</details>

<details>

<summary>2. Abertura de Documento Compartilhado</summary>

Corrigido erro ao acessar documentos compartilhados com senha.

❌ Mensagem removida: _“Usuário is not defined”_\
✅ Documento exibido corretamente após autenticação

</details>

<details>

<summary>3. Classificação após Importação Automática</summary>

Corrigida a exibição da classificação, que anteriormente mostrava apenas o código.

✅ Agora segue o padrão: Código | Assunto

</details>

🚀 Seguimos evoluindo o DocZ com foco em conformidade SBIS, segurança digital, rastreabilidade, integração e eficiência operacional.



{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Voltar</a>
