---
description: MENU > GESTÃO DE GUARDA > ARQUIVAR EM CONTAINER
---

# Arquivar em Container

A funcionalidade **Arquivamento em Containers** permite associar objetos documentais a um container principal, criando uma relação hierárquica entre os itens armazenados.

Esse recurso é utilizado para registrar quais documentos, mídias, caixas ou outros objetos estão acondicionados dentro de um container físico, facilitando o controle, a localização e a rastreabilidade dos itens durante as atividades de guarda, movimentação, inventário e auditoria.

O processo é realizado por meio da leitura (bipagem) dos identificadores SOS dos objetos envolvidos.

{% hint style="info" %}
**Importante**

Para que um objeto possa ser utilizado como container, seu **Tipo de Objeto** deve estar configurado com a opção **Container** habilitada no cadastro de Tipos de Objeto.

Essa configuração determina que o objeto poderá receber outros itens em sua estrutura de armazenamento.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

**Como funciona**

{% stepper %}
{% step %}
Informe ou bipar o **Identificador SOS do Container Principal**.
{% endstep %}

{% step %}
Em seguida, informe ou bipar o **Identificador SOS do objeto** que será armazenado dentro do container.
{% endstep %}

{% step %}
O sistema realizará automaticamente a associação entre os objetos.
{% endstep %}

{% step %}
Os itens vinculados serão exibidos na seção **Itens Arquivados**.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
Sucesso da ação!
{% endhint %}

**Exemplo de utilização**

```
Container Principal:
CX00001234 (Caixa 20kg)

Itens Arquivados:
CB00000456
CB00000457
MD00000123
DOC00007890
```

Neste exemplo, todos os objetos listados passam a estar vinculados à Caixa 20kg informada como container principal.



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
