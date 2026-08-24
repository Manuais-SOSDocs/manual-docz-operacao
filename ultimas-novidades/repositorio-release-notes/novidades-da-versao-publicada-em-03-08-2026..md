---
description: 'Versão: Docz v:2026.07.28.19.1.5.17.10'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 03/08/2026.

Nesta versão, o DocZ recebeu novas funcionalidades voltadas à ampliação das integrações via API, ao fortalecimento da segurança da informação, à evolução da gestão documental em conformidade com o e-ARQ Brasil e ao acompanhamento dos resultados da extração e validação por Inteligência Artificial. Também foram implementadas melhorias de estabilidade e correções na pesquisa documental.

### 📦 Novas Funcionalidades

#### 🤖 Painel Gerencial de Extração e Validação por IA

Foi disponibilizada a primeira versão do Painel Gerencial de Extração e Validação por IA, permitindo acompanhar indicadores consolidados dos metadados extraídos automaticamente pela Inteligência Artificial e posteriormente submetidos à validação humana.

Nesta primeira entrega, o painel disponibiliza:

* indicadores consolidados de volumetria;
* índices de assertividade e divergência da IA;
* métricas de campos corrigidos, mantidos e preenchidos manualmente;
* filtros por cliente, projeto, período, tipo documental e metadado;
* estrutura inicial das abas analíticas, preparada para futuras evoluções.

Benefícios: maior visibilidade sobre a qualidade da extração por IA, acompanhamento gerencial da validação humana, controle operacional dos resultados e geração de informações para a evolução contínua dos processos inteligentes.

#### 🔗 DocZ Integra – Novos endpoints para integrações

A API do DocZ foi ampliada com novos endpoints para automatizar operações de gestão documental e facilitar a integração com sistemas externos.

Foram disponibilizados recursos para:

* criação de pastas em projetos;
* consulta de pastas por ID;
* recuperação de documentos por classificação documental;
* classificação documental de documentos e caixas;
* validação e aprimoramento do endpoint de indexação de documentos, com suporte aos diferentes tipos de metadados.

_Todos os endpoints seguem as regras de autenticação e autorização da API do DocZ._

Benefícios: ampliação da capacidade de integração com sistemas corporativos, automatização de processos documentais, redução de atividades manuais e maior consistência na indexação e classificação documental.

#### 🔒 Aplicação de Grau de Sigilo em Pastas

Foi implementada a aplicação de Grau de Sigilo diretamente nas pastas de projetos, permitindo controlar o acesso aos objetos por meio de regras configuráveis e da herança automática do nível de sigilo para todo o conteúdo relacionado.

A funcionalidade contempla:

* configuração dinâmica dos níveis de sigilo por cliente;
* aplicação automática do sigilo aos documentos vinculados;
* controle de acesso baseado em permissões;
* identificação visual dos conteúdos protegidos;
* registro das operações na Trilha de Auditoria.

Benefícios: fortalecimento da segurança da informação, maior proteção de documentos sensíveis, controle refinado de acesso aos conteúdos e conformidade com requisitos arquivísticos e de governança.

#### 🏛️ \[E-ARQ] Exportação de Arquivos das Ordens de Serviço de Destinação

O processo de destinação documental foi aprimorado com a possibilidade de exportar, em lote, os arquivos e metadados vinculados às Ordens de Serviço dos seguintes tipos:

* Expurgo;
* Recolhimento;
* Saída Definitiva.

A exportação é processada de forma assíncrona pela Central de Downloads, e todas as operações são registradas automaticamente na Trilha de Auditoria.

Benefícios: exportação das listagens de objetos que estão sendo destinados, de acordo com cada tipo de OS.

#### 📊 \[E-ARQ] Relatório de Documentos por Classe Documental

Foi disponibilizado um novo relatório padrão para consultar documentos a partir de sua Classe Documental, facilitando a localização e o acompanhamento das informações classificadas conforme o Plano de Classificação.

_Disponível em: Relatórios → Relatórios Padrão._

O relatório permite:

* selecionar uma ou mais Classes Documentais;
* aplicar filtros para refinar a consulta;
* exportar os resultados para Excel;
* considerar automaticamente toda a hierarquia da classificação documental na geração do relatório.

Benefícios: maior rastreabilidade dos documentos classificados, apoio às atividades de auditoria e conformidade, agilidade na geração de informações gerenciais e melhor acompanhamento da classificação documental.

### 🛠️ Ajustes e Correções

<table data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><strong>Pesquisa de documentos por classificação documental</strong></p><p>Foi corrigido o comportamento que impedia a localização de documentos vinculados a códigos de classificação documental posteriormente desabilitados.</p><p><br>Agora, os códigos inativos não podem ser utilizados em novas classificações, mas permanecem disponíveis como critério de pesquisa para a localização dos documentos anteriormente classificados.</p></td></tr><tr><td><p><strong>Link do ambiente no e-mail de expiração de senha</strong></p><p>Foi corrigida a exibição do link de acesso apresentado no e-mail de expiração de senha. </p><p><mark style="color:$warning;"><strong>Antes:</strong></mark> o e-mail exibia a URL do ambiente de produção do DocZ para todos os clientes, embora o direcionamento do link estivesse correto.<br><mark style="color:$success;"><strong>Agora:</strong></mark> o endereço exibido corresponde dinamicamente ao ambiente de cada cliente.</p></td></tr><tr><td><p><strong>Importação de metadados</strong></p><p>Foi corrigido um erro no processo de importação de metadados, garantindo maior estabilidade e confiabilidade na execução da funcionalidade.</p></td></tr></tbody></table>



🚀 Seguimos evoluindo o DocZ com foco em conformidade SBIS, segurança digital, rastreabilidade, integração e eficiência operacional.

{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="../" class="button secondary" data-icon="circle-left">Voltar</a>
