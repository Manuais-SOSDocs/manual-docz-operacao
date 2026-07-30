# Relatórios de Ações de Usuários

A funcionalidade **Relatórios de Ações de Usuários** permite consultar e gerar relatórios relacionados às operações realizadas pelos usuários no sistema DocZ, especialmente atividades vinculadas à geração de etiquetas e processos de implantação, indexação e catalogação documental.

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

A tela apresenta filtros para definição dos critérios de pesquisa e geração dos relatórios.

#### **Filtros Disponíveis**

| Filtro                | Opções/Valores                             | Descrição                                                                                 | Objetivo                                                                                                     |
| --------------------- | ------------------------------------------ | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| **Cliente**           | Seleção de cliente cadastrado no sistema   | Permite selecionar o cliente para o qual o relatório será gerado.                         | Restringir a consulta às informações pertencentes a uma determinada instituição, órgão, empresa ou contrato. |
| **Tipo de Relatório** | **1 - EtiqPress - Etiqueta de Caixa 20KG** | Exibe registros relacionados à impressão de etiquetas para caixas padrão de 20 kg.        | Controlar e auditar impressões de etiquetas de caixas 20 kg.                                                 |
|                       | **2 - EtiqPress - Etiqueta de Caixa Box**  | Apresenta as impressões realizadas para caixas Box.                                       | Controlar e auditar impressões de etiquetas de caixas Box.                                                   |
|                       | **3 - EtiqPress - Etiqueta de Documento**  | Lista impressões de etiquetas individuais para documentos.                                | Monitorar a identificação documental realizada pelos usuários.                                               |
|                       | **4 - EtiqPress - Endereços Externos**     | Relaciona etiquetas ou registros associados a localizações externas ao armazém principal. | Acompanhar registros vinculados a endereços externos.                                                        |
|                       | **5 - EtiqPress - Endereçamentos**         | Apresenta informações de endereçamento físico dos objetos dentro da estrutura de guarda.  | Controlar a localização física dos objetos armazenados.                                                      |
| **Data Pesquisa**     | **Data Criação**                           | Data de criação do registro.                                                              | Consultar ações com base na criação dos registros.                                                           |
|                       | **Data Atualização**                       | Última alteração realizada no registro.                                                   | Identificar registros modificados em determinado período.                                                    |
|                       | **Data Distribuição**                      | Data de distribuição para tratamento operacional.                                         | Acompanhar distribuição de atividades ou objetos.                                                            |
|                       | **Data Indexação Inicial**                 | Data de início da indexação.                                                              | Monitorar o início dos trabalhos de indexação.                                                               |
|                       | **Data Indexação Final**                   | Data de conclusão da indexação.                                                           | Verificar documentos ou objetos indexados no período.                                                        |
|                       | **Data Cat. Complementar**                 | Data da catalogação complementar.                                                         | Controlar atividades complementares de catalogação.                                                          |
|                       | **Data Implantação**                       | Data de implantação do objeto no sistema.                                                 | Consultar registros implantados em determinado período.                                                      |
| **Data Inicial**      | Data selecionada pelo usuário              | Define o início do intervalo de pesquisa.                                                 | Limitar a consulta ao período desejado.                                                                      |
| **Data Final**        | Data selecionada pelo usuário              | Define o fim do intervalo de pesquisa.                                                    | Delimitar o período final da consulta e geração do relatório.                                                |

#### Ações disponíveis:

<table data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><img src="../../.gitbook/assets/image.png" alt=""><br>Realiza a consulta com os filtros informados e apresenta os resultados na grade inferior.</p><p><strong>Quando utilizar:</strong></p><ul><li>Conferência prévia dos dados;</li><li>Validação dos filtros;</li><li>Verificação de volume antes da geração do relatório.</li></ul></td></tr><tr><td><p><img src="../../.gitbook/assets/image (1).png" alt=""><br>Processa a consulta e envia o relatório para geração.</p><p><strong>Resultado:</strong></p><p>O relatório poderá ser disponibilizado para download após o processamento.</p></td></tr><tr><td><p><img src="../../.gitbook/assets/image (2).png" alt=""><br>Abre a Central de Downloads do DocZ para acompanhamento e obtenção dos arquivos gerados.</p><p><strong>Recomendação:</strong></p><p>Utilize esta opção após gerar relatórios com grandes volumes de dados.</p></td></tr></tbody></table>

<details>

<summary><mark style="color:$primary;"><strong>Exemplos de Utilização</strong></mark></summary>

<table data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><strong>Auditoria de Impressão de Etiquetas</strong></p><p><strong>Objetivo:</strong><br>Verificar quem realizou impressões de etiquetas de caixas em determinado período.</p><p>Configuração:</p><ul><li>Tipo: EtiqPress - Etiqueta de Caixa 20KG</li><li>Data Pesquisa: Data Criação</li><li>Período: mês desejado</li></ul></td></tr><tr><td><p><strong>Controle de Implantação</strong></p><p><strong>Objetivo:</strong><br>Identificar objetos implantados durante um período específico.</p><p>Configuração:</p><ul><li>Tipo: EtiqPress - Endereçamentos</li><li>Data Pesquisa: Data Implantação</li></ul></td></tr><tr><td><p><strong>Monitoramento da Indexação</strong></p><p><strong>Objetivo:</strong><br>Acompanhar documentos finalizados pela equipe de indexação.</p><p>Configuração:</p><ul><li>Data Pesquisa: Data Indexação Final</li><li>Período desejado</li></ul></td></tr></tbody></table>

</details>



<a href="./" class="button secondary" data-icon="circle-left">Voltar</a>
