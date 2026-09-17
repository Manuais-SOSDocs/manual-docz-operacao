---
description: 'Versão: DocZ v: Docz v:2026.09.02.20.bf11942f'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 03/09/2026.

Nesta versão, o DocZ recebeu melhorias voltadas à confiabilidade da gestão documental, à precisão das pesquisas e à continuidade das atividades operacionais. A atualização também contempla melhorias necessárias ao ambiente dedicado do GDF, incluindo ajustes no gerenciamento de armazéns.

## 🆕 Nova Funcionalidade

#### ✍️ Assinatura Digital com Embarque Dinâmico de Metadados em PDF

Esta entrega conclui a evolução iniciada com a Configuração Dinâmica para Embarque de Metadados em PDF.

Na fase inicial, o DocZ passou a disponibilizar, pela própria interface, o cadastro de regras, critérios e chaves de decisão por projeto. Nesta nova etapa, essas configurações passam a ser aplicadas automaticamente pelo motor de assinatura digital durante o processamento dos arquivos PDF.

Com essa evolução, os usuários autorizados da operação podem definir e manter as regras diretamente pela interface do DocZ. A criação ou alteração dessas configurações não depende mais da atuação do time de TI, da manutenção de arquivos estáticos ou da realização de configurações técnicas específicas.

O sistema identifica a regra aplicável conforme as definições realizadas para o projeto, considerando critérios de tipo documental. Quando não houver correspondência com uma regra específica, poderá ser utilizada a regra genérica definida para o projeto.

A interface permite configurar:

* Metadado de destino;
* Origem do valor por campo único, combinação de até três campos ou valor fixo;
* Campo de objetos, arquivos, projeto e clientes;
* Ordem dos campos e separador utilizado na composição;
* Configuração da assinatura visível;
* Utilização de carimbo de tempo.

As alterações realizadas nas regras e nos respectivos mapeamentos também são registradas na trilha de auditoria, ampliando a rastreabilidade das configurações.

**🎯 Benefícios**

* Maior autonomia para a operação configurar e manter as regras pela interface;
* Eliminação da dependência do time de TI para criação ou alteração das configurações;
* Aplicação automática das regras durante a assinatura dos PDFs;
* Maior flexibilidade na definição dos metadados documentais;
* Definição de regras por tipo documental dentro de um mesmo projeto;
* Redução da dependência de configurações estáticas e customizações por cliente;
* Maior aderência aos requisitos de gestão documental e ao Decreto nº 10.278/2020.

## 🛠️ Ajustes e Melhorias

#### 🔄 Classificação preservada no recálculo de prazos

Ao utilizar a opção Recalcular Prazo, no Controle de Prazos e Destinações, o DocZ passa a preservar todas as informações de classificação vinculadas ao objeto, atualizando somente os dados relacionados ao prazo.

**🎯 Benefícios**

* Maior segurança e consistência das informações;
* Redução da necessidade de reclassificação e retrabalho.

#### 📥 Importação de objetos mais clara

A funcionalidade de importação passa a informar que a coluna C1 é obrigatória na planilha, facilitando a preparação e a validação dos arquivos antes do processamento.

**🎯 Benefícios**

* Mais clareza no preenchimento das planilhas;
* Redução de falhas durante a importação.

#### 🖼️ Navegação por Fotolabel

A navegação por fotolabel foi ajustada para apresentar corretamente os arquivos vinculados às caixas armazenadas no DocZ.

**🎯 Benefícios**

* Maior confiabilidade na localização dos documentos;
* Mais agilidade nos processos de consulta e comprovação.

#### 🗃️ Maior precisão na destinação para Guarda Permanente

No Controle de Prazos e Destinações, as pesquisas com Destinação Final = Guarda Permanente passam a apresentar exclusivamente documentos com status Arquivado, garantindo que somente objetos aptos sejam disponibilizados para esse fluxo.

**🎯 Benefícios**

* Maior consistência no processo de destinação documental;
* Redução do risco de seleção de documentos com status incompatível.

**Ajustes no ambiente dedicado do GDF - Clientes SEDET e JUCIS**

#### 🏢 Ajuste no cadastro de armazéns

O fluxo de cadastro de armazéns foi aprimorado para permitir a inclusão em ambientes que ainda não possuem unidades previamente cadastradas.

**🎯 Benefícios**

* Maior continuidade na configuração dos ambientes;
* Mais agilidade na estruturação dos locais de guarda.



🚀 Seguimos evoluindo o DocZ com foco em conformidade SBIS, segurança digital, rastreabilidade, integração e eficiência operacional.

{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Voltar</a>
