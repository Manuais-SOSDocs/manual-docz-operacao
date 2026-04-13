---
description: 'Versão: Docz v:2026.03.31.17.1.5.17.1'
hidden: true
icon: bullhorn
---

# Novidades da Versão Publicada em 31/03/2026.

## Confira as últimas melhorias e correções implementadas no sistema DocZ.

<table data-card-size="large" data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><mark style="color:$primary;"><strong>1. 🔒 Controle de inatividade de usuário na sessão</strong></mark></p><p></p><p>Agora é possível configurar, por Cliente, o tempo de inatividade do usuário, permitindo o bloqueio automático da sessão após um período sem interação.<br>A funcionalidade considera a ausência de ações para contagem do tempo, reiniciando esse controle a cada nova interação.</p><p><br><em><mark style="color:$info;">🔐 Ao atingir o limite configurado, o usuário é automaticamente bloqueado e redirecionado para novo login, com a configuração devidamente persistida para garantir segurança e controle de acesso.</mark></em></p></td></tr><tr><td><p><mark style="color:$primary;"><strong>2.🔐 Rastreabilidade na alteração de CPF</strong></mark></p><p></p><p>Agora, ao alterar o CPF de um usuário, o sistema passa a exigir o preenchimento de uma justificativa obrigatória para conclusão da ação.<br>A medida reforça o controle sobre mudanças sensíveis, garantindo maior segurança e auditabilidade.<br></p><p><em><mark style="color:$info;">📌 As informações da alteração, incluindo CPF anterior, usuário responsável, data e hora, são registradas e persistidas na Trilha de Auditoria.</mark></em></p></td></tr><tr><td><p><mark style="color:$primary;"><strong>3.🔐 Controle de tentativas de login</strong></mark></p><p></p><p>Foi criado um novo parâmetro em Clientes para definir o número máximo de tentativas de login antes do bloqueio do usuário.<br>A funcionalidade aumenta a segurança ao impedir acessos após erros consecutivos de credenciais, realizando o bloqueio imediato ao atingir o limite definido. </p><p><br><em><mark style="color:$info;">⚠️ Caso não configurado, o sistema adota o padrão de 5 tentativas, com limite máximo de até 10, garantindo controle e proteção adicionais.</mark></em></p></td></tr><tr><td><p><mark style="color:$primary;"><strong>4. 📊 Ajuste no cálculo de prazo de guarda</strong></mark></p><p></p><p>Aprimorada a regra de negócio para garantir que apenas registros elegíveis sejam considerados nas listagens geradas pelo, respeitando o ano corrente e os critérios de destinação final. </p><p></p><p><em><mark style="color:$info;">✅ Isso traz mais precisão e confiabilidade aos resultados.</mark></em></p></td></tr><tr><td><p><mark style="color:$primary;"><strong>5. 🧩 Espelho Personalizado (SPGG)</strong></mark></p><p></p><p>Implementado espelho customizado para o cliente SPGG, com layout e regras adaptadas às suas necessidades.</p></td></tr><tr><td><p><mark style="color:$primary;"><strong>6. 🛠️ Correção em Calcular Rotas</strong></mark></p><p></p><p>Corrigido erro que impedia o uso da funcionalidade no menu Calcular Rotas, em Solicitações.</p><p>A tela de “Dados da Rota” volta a carregar normalmente, sem falhas, garantindo a continuidade das operações.</p></td></tr></tbody></table>





{% hint style="info" %}
Ficou com dúvidas ou quer saber mais? Fale com o time de [Suporte](https://sosdocs.atlassian.net/servicedesk/customer/portal/9)
{% endhint %}



<a href="./" class="button secondary" data-icon="circle-left">Retornar para anterior</a>
