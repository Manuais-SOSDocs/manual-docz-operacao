---
hidden: true
---

# Como cadastrar e editar projetos.

### Como criar um novo projeto 👇

{% stepper %}
{% step %}
Acesse no menu lateral "Projetos"
{% endstep %}

{% step %}
Na grid “Selecione o Projeto”, clique no ícone  ![](<../.gitbook/assets/image (239).png>) para criar um novo projeto.
{% endstep %}

{% step %}
Na grid abaixo, preencha o [formulário ](como-cadastrar-e-editar-projetos..md#explorando-o-formulario)com as especificações do projeto.

<div align="left"><figure><img src="../.gitbook/assets/image.png" alt="" width="563"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Ao finalizar, clique em ![](<../.gitbook/assets/image (240).png>)
{% endstep %}
{% endstepper %}

{% hint style="success" %}
**Projeto Criado com sucesso!**
{% endhint %}



### **Como editar um projeto** ✏️&#x20;

Nesta seção, o usuário pode ajustar as configurações gerais do projeto, definindo limites operacionais, permissões de uso e parâmetros específicos de funcionamento.

{% stepper %}
{% step %}
Acesse no menu lateral "Projetos"
{% endstep %}

{% step %}
Na grid “Selecione o Projeto”, escolha o projeto que deseja editar.
{% endstep %}

{% step %}
Na grid **“Projeto”**, clique no ícone  ![](<../.gitbook/assets/image (242).png>)  para editar o projeto.
{% endstep %}

{% step %}
Na grid abaixo, faça as alterações necessárias conforme as especificações desejadas.
{% endstep %}

{% step %}
Ao finalizar, clique em ![](<../.gitbook/assets/image (240).png>) para aplicar as mudanças.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
**Projeto editado com sucesso!**
{% endhint %}

<details>

<summary>📌 Personalização da <strong>assinatura exibida nas Ordens de Serviço (OS)</strong></summary>

É possível configurar a **assinatura exibida nas Ordens de Serviço (OS)**, escolhendo entre:

* **Nome do Cliente**
* **Nome do Projeto**
* **Ambos (Cliente + Projeto)**

</details>

### 📋Explorando o formulário

<figure><img src="../.gitbook/assets/image.png" alt="" width="563"><figcaption></figcaption></figure>

<table><thead><tr><th width="263.45458984375">Campo</th><th>Explicação</th></tr></thead><tbody><tr><td><strong>Nome</strong></td><td>Identificação do projeto. Deve ser único e claro para fácil localização.</td></tr><tr><td><strong>Descrição</strong></td><td>Texto livre para detalhar a finalidade ou escopo do projeto.</td></tr><tr><td><strong>Limite de solicitação diária</strong></td><td>Define quantas solicitações podem ser feitas por dia neste projeto.</td></tr><tr><td><strong>Limite de objetos para indexação por lotes</strong></td><td>Determina a quantidade máxima de objetos que podem ser indexados de uma só vez.</td></tr><tr><td><strong>Código Guarda</strong></td><td>Código de referência para gestão ou classificação do projeto no repositório. <sup>(esse campo não pode ser alterado)</sup></td></tr><tr><td><strong>Configurar Fuso Horário Padrão (UTC)</strong></td><td>Essa configuração estabelece a referência temporal que será utilizada pelo sistema para exibição, conversão e interpretação de todos os registros de data e hora associados ao respectivo projeto.</td></tr><tr><td><strong>Armazém</strong></td><td>Local (físico ou digital) onde os documentos do projeto serão armazenados.</td></tr><tr><td><strong>Ativo</strong></td><td>Indica se o projeto está em uso ou inativo.</td></tr><tr><td><strong>Principal</strong></td><td>Define se este projeto será o principal dentro do sistema.</td></tr><tr><td><strong>Armazenar Documentos Digitais no Docz File Service</strong></td><td>Habilita o armazenamento no serviço de arquivos do sistema.</td></tr><tr><td><strong>Permite Imprimir Etiquetas</strong></td><td>Autoriza a geração e impressão de etiquetas para organização física.</td></tr><tr><td><strong>Permite Adicionar Arquivo(s)</strong></td><td>Permite incluir novos arquivos no projeto.</td></tr><tr><td><strong>Pode Solicitar Caixa?</strong></td><td>Autoriza requisições de caixas físicas vinculadas ao projeto.</td></tr><tr><td><strong>Pode Solicitar Documento?</strong></td><td>Permite a solicitação de documentos armazenados no projeto.</td></tr><tr><td><strong>Disponibilizar Registro Fotográfico</strong></td><td>Permite anexar fotos como parte do atendimento da O.S.</td></tr><tr><td><strong>Inserir Vinculados Solicitação</strong></td><td>Possibilita relacionar documentos/objetos vinculados a uma solicitação.</td></tr><tr><td><strong>Ver Integrações</strong></td><td>Permite visualizar integrações ativas do projeto com outros sistemas.</td></tr><tr><td><strong>Compartilhar Pacotes de Preservação</strong></td><td>Possibilita compartilhar pacotes de preservação digital.</td></tr><tr><td><strong>Habilitar Envio para o SEI</strong></td><td>Ativa a integração com o SEI (Sistema Eletrônico de Informações).</td></tr><tr><td><strong>Permitir Digitalizar</strong></td><td>Libera a funcionalidade de digitalização de documentos.</td></tr><tr><td><strong>Visualizar Versões</strong></td><td>Permite visualizar versões anteriores dos documentos.</td></tr><tr><td><strong>Permite liberar objetos sem tipologia</strong></td><td>Libera objetos para avaliação mesmo sem tipologia definida.</td></tr><tr><td><strong>Permite Arquivar/Desarquivar</strong></td><td>Permite enviar documentos para arquivamento e reabri-los.</td></tr><tr><td><strong>Permitir Relacionamentos</strong></td><td>Possibilita relacionar documentos entre si.</td></tr><tr><td><strong>Notificar Expurgo por E-mail</strong></td><td>Envia alerta por e-mail quando um documento for expurgado.</td></tr><tr><td><strong>Periodicidade do envio de e-mail de expurgo em dias</strong></td><td>Define de quantos em quantos dias o sistema enviará o e-mail de notificação.</td></tr><tr><td><strong>Período a ser considerado no relatório de expurgo enviado:</strong></td><td>Aqui você define qual intervalo de tempo será considerado dentro do relatório que será enviado por e-mail.</td></tr><tr><td><strong>Controlar Vencimento de Empréstimo</strong></td><td>Habilita controle automático de prazos de empréstimos de objetos.</td></tr><tr><td><strong>Prazo padrão para devolução de objeto (em dias)</strong></td><td>Define <strong>quantos dias o usuário terá, por padrão, para devolver o objeto emprestado</strong>.</td></tr><tr><td><strong>Permitir alteração do prazo</strong><br><strong>pelo solicitante</strong></td><td>Quando marcado, o usuário que está solicitando o empréstimo poderá alterar o prazo de devolução.</td></tr><tr><td><strong>Dia do mês para envio de notificação de empréstimo vencido</strong></td><td>Define em qual dia do mês o sistema enviará notificações sobre empréstimos que estão vencidos ou próximos do vencimento.</td></tr><tr><td><strong>Tempo de inatividade para bloqueio do usuário(em dias)</strong></td><td><strong>Determina quantos dias o usuário pode ficar sem acessar o sistema antes de ser bloqueado automaticamente.</strong></td></tr><tr><td><strong>Compartilhar Arquivos pela Pesquisa</strong></td><td>Permite compartilhar documentos diretamente da pesquisa.</td></tr><tr><td><strong>Compartilhar Arquivos pela Solicitação</strong></td><td>Permite compartilhar arquivos durante uma solicitação.</td></tr><tr><td><strong>Restringir Acesso por Departamento</strong></td><td>Restringe acesso a documentos apenas para o departamento do usuário.</td></tr><tr><td><strong>Substituir Arquivo de Fotolabel</strong></td><td>Autoriza a substituição de arquivos de fotolabel.</td></tr><tr><td><strong>Realizar Chancela em Documentos Digitalizados</strong></td><td>Permite aplicar chancela em documentos digitalizados.</td></tr><tr><td><strong>Realizar Chancela em Documentos Digitalizados em Lote</strong></td><td>Permite aplicar chancela em vários documentos digitalizados de uma vez.</td></tr><tr><td><strong>Adicionar Marca d’Água</strong></td><td>Insere marca d’água em documentos digitalizados.</td></tr><tr><td><strong>Realizar Assinatura com Certificado Pessoal</strong></td><td>Permite assinar documentos com certificado digital.</td></tr><tr><td><strong>Realizar Assinatura em Lote</strong></td><td>Permite assinar múltiplos documentos de uma só vez.</td></tr><tr><td><strong>Finalizar O.S Digital com 2 Fatores</strong></td><td>Adiciona autenticação em dois fatores para finalização de O.S.</td></tr><tr><td><strong>Formato de Assinatura da O.S.</strong></td><td>Define o formato que será utilizado na assinatura das O.S.</td></tr><tr><td><strong>Campos da Descrição da Solicitação – Documentos</strong></td><td>Define os campos obrigatórios para solicitação de documentos.</td></tr><tr><td><strong>Campos da Descrição da Solicitação – Caixas</strong></td><td>Define os campos obrigatórios para solicitação de caixas.</td></tr><tr><td><strong>Pesquisa Personalizada</strong></td><td>Permite configurar filtros de pesquisa personalizados.</td></tr><tr><td><strong>Enviar Notificação de O.S.</strong></td><td>Envia notificações automáticas sobre O.S. por e-mail.</td></tr><tr><td><strong>Obrigatoriedade de destinatário na abertura da O.S</strong></td><td><p>Define se será obrigatório informar para quem a Ordem de Serviço será direcionada no momento da abertura.</p><ul><li>Marcado → não é possível abrir a O.S. sem definir um destinatário</li><li>Desmarcado → a O.S. pode ser aberta sem responsável definido inicialmente</li></ul></td></tr><tr><td><strong>Enviar Relatório de Expurgo Anualmente Automaticamente</strong></td><td>Quando ativado, o sistema irá gerar e enviar automaticamente um relatório consolidado de expurgos uma vez por ano.</td></tr><tr><td><strong>E-Mail Email Notificação de Relatório de Expurgo</strong></td><td>ampo destinado a informar qual endereço de e-mail receberá os relatórios automáticos de expurgo.</td></tr><tr><td><strong>E-mail Cliente Comunicações/Notificações</strong></td><td>Endereço de e-mail que receberá comunicações do sistema.</td></tr><tr><td><strong>E-mail Cliente Notificações Lotes</strong></td><td>Endereço de e-mail para notificações de lotes.</td></tr><tr><td><strong>E-mail Gestão Documental</strong></td><td>E-mail responsável pela gestão documental.</td></tr><tr><td><strong>E-mail Digitalização</strong></td><td>E-mail utilizado para notificações sobre digitalização.</td></tr><tr><td><strong>E-mail Notificação Novos Arquivos</strong></td><td>E-mail que recebe notificações sempre que novos arquivos são adicionados.</td></tr><tr><td><strong>Notificar Vencimento de SLA (Normal)</strong></td><td>Ativa notificações para vencimento de prazos normais (SLA).</td></tr><tr><td><strong>Notificar Vencimento de SLA</strong><br><strong>(Prioridade Normal)</strong></td><td>Quando marcado, o sistema passa a enviar alertas sobre vencimento de SLA de atividades classificadas como prioridade normal.</td></tr><tr><td><strong>E-mail</strong></td><td>Indica quem receberá essas notificações de SLA normal.</td></tr><tr><td><strong>Tempo de Aviso Prévio (Normal) - Horas</strong></td><td>Define com quantas horas de antecedência o sistema enviará o alerta antes do vencimento do SLA.</td></tr><tr><td><strong>Notificar Vencimento de SLA (Urgente)</strong></td><td>Ativa notificações para vencimento de prazos urgentes.</td></tr><tr><td><strong>Mostrar Dados do Responsável</strong><br><strong>pelo Transporte na O.S.</strong></td><td>Quando marcado, o sistema passa a exibir nas Ordens de Serviço as informações do responsável pelo transporte físico do material.</td></tr><tr><td><strong>E-mail</strong></td><td>Define quem receberá os alertas de vencimento de SLA urgente.</td></tr><tr><td><strong>Tempo de Aviso Prévio (Urgência) - Horas</strong></td><td>Funciona igual ao SLA normal, porém aplicado às demandas urgentes.</td></tr><tr><td><strong>Habilitar Valores Padrão para Metadados</strong></td><td>Define valores padrão automáticos para metadados de arquivos.</td></tr><tr><td><strong>Autor</strong></td><td>Define o autor padrão atribuído aos arquivos cadastrados no projeto.</td></tr><tr><td><strong>Local da Digitalização</strong></td><td>Indica o local físico ou unidade onde ocorreu a digitalização do documento.</td></tr><tr><td><strong>Responsável da Digitalização</strong></td><td>Define o nome do responsável técnico ou equipe pela digitalização.</td></tr><tr><td><strong>Local de Produção</strong></td><td><strong>Refere-se ao local onde o documento foi originalmente produzido (origem documental).</strong></td></tr></tbody></table>



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
