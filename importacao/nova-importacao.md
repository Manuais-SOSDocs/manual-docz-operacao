---
description: >-
  A funcionalidade de Importação de Metadados permite a inclusão ou atualização
  em massa de registros no DocZ e aplicação automática de regras de
  classificação configuradas.
---

# Nova importação

Esta tela permite realizar a importação em massa de metadados no DocZ, com a opção de aplicar automaticamente a classificação dos registros conforme regras previamente configuradas.

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

#### 📥 Passo a passo para realizar a importação de metadados

{% stepper %}
{% step %}
No **menu lateral**, acesse:\
**Importação → Nova Importação**.
{% endstep %}

{% step %}
No campo **Projeto**, selecione o projeto no qual os metadados serão importados.

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Na **grade à esquerda**, serão exibidas as pastas existentes no repositório do projeto selecionado.

Selecione a pasta para a qual deseja importar os metadados.

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Na **grade à direita**, será exibida a lista e a ordem dos campos que devem ser preenchidos para a importação.

Nessa mesma área, o usuário pode **realizar o download do modelo** de importação, disponível nos formatos **Excel ou CSV**.

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Após o download do modelo, o usuário deverá definir os seguintes parâmetros de importação, conforme necessidade:

* **Desconsiderar Localização para importação**
* **Aplicar Classificação Automática**
* **Data para Importação** (formato dd/mm/aaaa)

{% hint style="info" %}
As importações são iniciadas na data agendada, sempre às **20:00**. Caso a data não seja informada, a importação será executada imediatamente.
{% endhint %}

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Após preencher corretamente o modelo de importação, realize o **upload do arquivo** na tela.

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Para concluir o processo, clique em <img src="../.gitbook/assets/image (14).png" alt="" data-size="line"> para iniciar ou programar o processamento.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
Ação concluída.
{% endhint %}

<details>

<summary><mark style="color:$info;"><strong>🔁 Regras de Processamento da Importação</strong></mark></summary>

Durante o processo de importação de metadados, o sistema avalia o campo **Identificador SOS** para definir como cada registro será tratado:

* **Identificador SOS vazio**:\
  Quando o campo estiver vazio, o sistema entende que se trata de um novo registro e **gera automaticamente uma nova etiqueta**, criando o objeto no DocZ.
* **Identificador SOS existente**:\
  Quando o identificador informado já existir no sistema, o DocZ **atualiza os metadados do registro correspondente**, mantendo o vínculo com o objeto já cadastrado.
* **Identificador SOS inválido**:\
  Caso o identificador informado não seja reconhecido pelo sistema, o registro **não é importado** e uma **mensagem de erro** é exibida, indicando a inconsistência.
* **Preservação dos metadados existentes**:\
  Os metadados já cadastrados no sistema **são mantidos** sempre que não forem explicitamente sobrescritos no arquivo de importação, garantindo a integridade das informações.

</details>



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
