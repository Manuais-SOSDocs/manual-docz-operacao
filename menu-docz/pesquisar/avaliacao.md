---
hidden: true
icon: folder-check
---

# Avaliação

A funcionalidade de avaliação é utilizada para a conferência, validação e aprovação dos objetos documentais carregados no sistema.

Seu principal objetivo é garantir a verificação das imagens digitalizadas e dos metadados indexados antes que os documentos avancem para as próximas etapas do fluxo documental.

{% hint style="info" %}
#### Campo “Etapa Documental”

O campo **“Etapa Documental”** é atualizado automaticamente conforme o avanço do lote no fluxo de avaliação.

Ele indica o status atual do lote, auxilia no controle do processo e pode atuar como gatilho para integrações automáticas com sistemas externos.
{% endhint %}

#### Como funciona a Tela de Avaliação

Ao acessar a tela de **Avaliação**, o usuário deve seguir os passos abaixo:

1. Utilize o campo _Status do Lote_ para selecionar a situação que deseja consultar (ex.: _Aguardando Aprovação_).
2. No campo _Limite de Registros_, o usuário poderá escolher quantos objetos deseja visualizar por página (ex.: 10, 20, 50, 100).
3. Clique em <mark style="color:blue;">**Pesquisar**</mark> para carregar os resultados de acordo com os filtros aplicados.

<figure><img src="../../.gitbook/assets/image (421).png" alt=""><figcaption></figcaption></figure>

### Fluxo de avalição em lote:

{% stepper %}
{% step %}
#### Criando o lote

Os objetos documentais que já passaram pelas etapas de digitalização e indexação, e que estejam com a etapa documental definida como **“Liberado para Avaliação”**, poderão ser selecionados para composição de um lote de avaliação.

<figure><img src="../../.gitbook/assets/image (515).png" alt=""><figcaption></figcaption></figure>

Após selecionar os objetos desejados, o usuário deverá clicar na opção **“Criar Lote”** para encaminhar os documentos ao fluxo de revisão e aprovação.

O lote criado reunirá os objetos documentais selecionados em uma única estrutura de avaliação, permitindo o acompanhamento centralizado das etapas de conferência, correção, aprovação, assinatura e envio para sistemas externos.

<figure><img src="../../.gitbook/assets/image (516).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Primeira etapa de revisão

Na primeira etapa, o revisor da operação SOS realiza a conferência dos documentos digitalizados e dos metadados indexados.

<figure><img src="../../.gitbook/assets/image (517).png" alt=""><figcaption></figcaption></figure>

Caso algum objeto apresente inconsistências, erros de indexação ou problemas documentais, o revisor poderá utilizar a opção **“Marcar como pendente”** de forma individual para o objeto.

Ao marcar o objeto como pendente:

* torna-se obrigatório informar uma justificativa;
* o motivo da pendência ficará registrado na aba **“Comentários”** da View Object;
* o fluxo do lote ficará bloqueado até que as correções sejam realizadas.

<figure><img src="../../.gitbook/assets/image (519).png" alt=""><figcaption></figcaption></figure>

Após os ajustes, o lote retorna novamente para a primeira etapa de revisão, onde será reavaliado.

Se todas as informações estiverem corretas, o lote será liberado para a próxima etapa.

<figure><img src="../../.gitbook/assets/image (509).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Segunda etapa de revisão

A segunda etapa de revisão pode ser realizada pela operação SOS, por gestores responsáveis ou até mesmo pelo cliente, conforme a configuração do fluxo do projeto.

Nessa fase, o revisor poderá:

* liberar o lote para a aprovação;
* ou retornar o lote para correções, reiniciando novamente o processo de revisão.

<figure><img src="../../.gitbook/assets/image (510).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Aprovação do lote

Quando o lote é liberado para a aprovação na segunda etapa de revisão, ele segue o fluxo para a etapa final da avaliação.

A aprovação confirma que os documentos e metadados foram validados corretamente e que o lote está apto para conclusão do processo documental.

<figure><img src="../../.gitbook/assets/image (520).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
#### Assinatura e envio para sistemas externos

Após a aprovação do lote, o sistema executa automaticamente a rotina de assinatura dos documentos, conforme as regras e parametrizações definidas no projeto.

Quando previsto no escopo da operação, após a assinatura o DocZ também realiza o envio automático dos objetos documentais para sistemas externos integrados.

O envio pode ser realizado para diferentes plataformas utilizadas pelo cliente, como:

* SEI;
* GEDs corporativos;
* sistemas próprios;
* ou outros sistemas integrados.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
O campo **“Etapa Documental”** será atualizado automaticamente conforme o avanço do fluxo, podendo apresentar status como:

* Concluído;
* Assinado;
* Enviado para _Sistema Externo/ RDC-arq_.
{% endhint %}



<a href="./#acoes-disponiveis-localizadas-acima-da-grade-projeto" class="button secondary" data-icon="circle-left">Voltar</a>
