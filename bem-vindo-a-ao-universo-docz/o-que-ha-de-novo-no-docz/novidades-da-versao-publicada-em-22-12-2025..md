---
description: 'Versão: DocZ v:2025.12.22.19.1.5.13.1'
icon: bullhorn
---

# Novidades da Versão Publicada em 22/12/2025.

## Confira as últimas melhorias e correções implementadas no sistema DocZ.

#### ✨ Novas Funcionalidades e Melhorias

* <mark style="color:blue;">**📈 Novo menu – Relatório de Ações de Usuário:**</mark>

Criado um novo submenu em Relatórios, voltado a relatórios gerenciais, com controle de permissão por usuário. Nesta primeira entrega, está disponível o relatório de impressão de etiquetas do EtiqPress, permitindo rastrear etiquetas impressas e não utilizadas. Próximas evoluções incluirão relatórios de produtividade por usuário.

* <mark style="color:blue;">**🏢 Gestão de colaboradores por unidade:**</mark>

Implementada a configuração de usuários por unidade de armazenamento/galpão, permitindo definir papéis e permissões específicas. A funcionalidade garante segregação entre unidades, controle de acesso a caixas e endereços e maior rastreabilidade das operações, como parte do módulo de auditoria.

* <mark style="color:blue;">**🧩 Reorganização de permissões:**</mark>

Reestruturação visual das permissões do DocZ em abas temáticas, melhorando a separação lógica, a usabilidade e facilitando a manutenção.

* <mark style="color:blue;">**🔎 Habilitar pesquisa de terceiros:**</mark>

Adicionada a opção de configurar campos do projeto como Habilitar pesquisa de terceiros, permitindo consultas mais flexíveis por sistemas externos integrados com o DocZ. As APIs foram ajustadas para suportar essa configuração e viabilizar integrações.

#### 🛠️ Correções e Ajustes

* <mark style="color:blue;">**🚚 Transporte:**</mark> Correção no acompanhamento de transporte que impedia a visualização da rota do veículo em tempo real ao utilizar a opção _Acompanhar Transporte_.
* <mark style="color:blue;">**📊 Relatórios:**</mark> Ajuste na extração de relatórios para desconsiderar DCs excluídas, garantindo que apenas registros ativos e presentes nas pastas válidas do projeto sejam exibidos.
* <mark style="color:blue;">**📦 Espelho de Caixa (SESC/SENAC-GO):**</mark> Foram realizados ajustes nos metadados exibidos no espelho definitivo de caixas, conforme solicitado.
* <mark style="color:blue;">**🔌 API – Integração com Docfy:**</mark> Ajustada a permissão de acesso via API que ocasionava erro 403 no envio e recuperação de metadados do DocZ.
* <mark style="color:blue;">**🔐 Autenticação:**</mark> Correção de bug que solicitava a redefinição de senha de forma recorrente, mesmo após a troca bem-sucedida. A validação da senha agora ocorre corretamente.

{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="./" class="button secondary" data-icon="circle-left">Retornar para anterior</a>
