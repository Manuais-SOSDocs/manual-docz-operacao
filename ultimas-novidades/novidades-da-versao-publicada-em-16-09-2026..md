---
description: 'Versão: Docz v:2026.09.16.21.570f4882'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 16/09/2026.

Nesta versão, o DocZ recebe melhorias importantes na experiência de uso, gestão documental e integrações. Entre os destaques estão a reformulação da tela de configuração de projetos, a evolução da gestão de relacionamentos entre documentos, novas orientações nos formulários de indexação e ajustes no controle da Tabela de Temporalidade.

## 📦 Novas Funcionalidades e Melhorias

#### 🔗 Gestão de Relacionamentos entre Documentos

A funcionalidade de relacionamentos entre documentos foi reformulada e incorporada à View Object, facilitando a visualização e o gerenciamento dos vínculos entre documentos diretamente em seu contexto.

Também foram implementadas novas regras de segurança para os processos de destinação e eliminação: documentos que possuam relacionamentos ativos não poderão ser destinados individualmente. Para prosseguir, será necessário remover o relacionamento ou incluir os documentos relacionados na mesma Ordem de Serviço.

A evolução amplia a rastreabilidade dos vínculos documentais e reforça a aderência do DocZ ao e-ARQ Brasil.

#### ⚙️ Nova organização da tela de configuração de Projetos

A tela de edição de projetos foi reorganizada para facilitar a localização e configuração dos parâmetros disponíveis no DocZ.

A nova interface conta com:

* organização das configurações por abas temáticas;
* pesquisa de parâmetros;
* painéis expansíveis para configurações complementares;
* melhor organização visual das opções disponíveis.

A alteração é exclusivamente de interface e mantém as regras de negócio e configurações existentes.

#### 📝 Descrição dos campos nos Formulários de Indexação

Agora é possível cadastrar uma descrição para os campos dos formulários de indexação.

A orientação é apresentada abaixo do respectivo campo durante a indexação, auxiliando o usuário no correto preenchimento das informações e tornando os formulários mais intuitivos.

#### ⏱️ Aviso de cobrança no Carimbo de Tempo

Na funcionalidade de Embarque de Metadados, foi incluído um aviso em destaque na parâmetro de Carimbo de Tempo, informando ao usuário que sua utilização possui custo.

A melhoria aumenta a transparência sobre o uso do recurso e permite que o usuário tenha conhecimento da possibilidade de cobrança antes de acioná-lo.

#### 🔌 Integração DocZ–SEI/EMGEA

A integração entre o DocZ e o SEI/EMGEA foi ajustada para garantir o correto preenchimento do campo “Número” dos documentos enviados.

O campo passa a utilizar o Identificador SOS correspondente ao documento, aumentando a consistência e a rastreabilidade das informações transmitidas entre os sistemas.

## 🛠️ Correções e Ajustes

#### 📋 Formulários – botão Salvar

Corrigida a duplicidade do botão “Salvar” na tela de configuração dos formulários.

A interface passa a apresentar apenas um botão para a ação, devidamente posicionado conforme o padrão visual da funcionalidade.

#### 📍 Pesquisa de itens por endereço de pallet

Corrigido o comportamento da pesquisa por endereço de pallet que poderia retornar resultados de endereços com nomes parcialmente correspondentes.

A consulta passa a considerar corretamente o endereço informado, evitando conflitos em situações como buscas por G2/G23 ou G1/G10.



🚀 Seguimos evoluindo o DocZ com foco em conformidade SBIS, segurança digital, rastreabilidade, integração e eficiência operacional.

{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
