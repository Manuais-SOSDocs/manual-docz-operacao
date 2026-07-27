---
description: 'Versão: DocZ v: 2025.11.05.18.1.5.7.1'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 06/11/2025.

## Confira as últimas melhorias e correções implementadas no sistema DocZ.

### ✨ Melhorias

#### 🗂 Envio ao Eternal:&#x20;

Aperfeiçoado o processo de envio de documentos ao repositório Eternal para registros provenientes de outros sistemas (SGE e SmartDocs).\
O envio agora considera, além da etapa documental, os metadados de arquivo, definindo o envio conforme o valor do campo “Observação”.\
Quando realizado, o UUID do pacote é registrado no campo “Identificador”, garantindo o controle de vínculo entre os documentos do DocZ e os pacotes do Eternal.

#### 📦 Campos “Origem” e “Destino” em O.S. de Movimentação:&#x20;

Incluídos dois novos campos obrigatórios para registrar o local de saída e o destino dos objetos, com listas suspensas exibindo os galpões da SOS cadastrados no DocZ.\
Os campos estão disponíveis exclusivamente para ordens de serviço de movimentação.

#### ✉️ Envio automático de e-mails com anexo da O.S.:&#x20;

Implementado o envio automático de e-mails com o PDF da O.S. para o endereço configurado em “E-Mail Cliente Comunicações/Notificações”, abrangendo todas as movimentações de caixa.\
A mensagem segue o padrão do sistema, incluindo cliente, projeto, usuário solicitante, data e código da O.S., além da observação de que se trata de um e-mail automático não respondível, garantindo rastreabilidade completa das movimentações.

### 🧩 Correções

#### 🗃 Formulário de Indexação:

Corrigido o posicionamento e comportamento do botão “Excluir”, que agora é exibido corretamente na coluna “Excluir” e remove apenas o DC da lista de indexação, sem excluí-lo da pasta de Documentos.

#### ⚙️ Importação e Classificação Automática:

Corrigidos bugs no processo de importação e classificação, garantindo a validação correta das regras e permitindo a recriação de regras previamente excluídas.



{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Retornar para anterior</a>
