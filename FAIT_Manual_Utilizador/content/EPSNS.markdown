---
layout: default
title: "EPSNS"
---

<p id="EPSNS"></p>
# 5. Módulos Perfil EPSNS
O utilizador associado ao perfil EPSNS, após efetuar o login à plataforma FAIT (Capítulo 4.1), visualiza um conjunto de módulos, onde poderá efetuar todas as ações a que possui permissão.

![figModulosEPSNS](img/capitulo5/Modulos.png)

<p class="caption" id="figModulosEPSNS">Módulos Perfil EPSNS </p>

<p id="registarFatura"></p>
## 5.1.Módulo Registar Fatura
O módulo de Registar Fatura permite ao utilizador com o perfil EPSNS, efetuar o registo manual de uma fatura referente as despesas com cuidados de saúde de utentes que tenham apresentado um documento de atestado de direito válido. O utilizador pode aceder a este módulo, na página inicial, ao clicar no seguinte ícone.

![figModuloRegFatura](img/capitulo5/5_1ModuloRegFatura.png)

<p class="caption" id="figModuloRegFatura">Módulo Registar Fatura </p>

O utilizador é então reencaminhado para a página que contém o formulário utilizado para o registo da fatura.

FIGURA 10 - FORMULÁRIO E125

O formulário apresenta-se subdividido em seis painéis:
* Instituição Remetente;
* Instituição Devedora;
* Pedido Individual;
* Documento Comprovativo do Direito a Prestação;
* Prestação concedida;
* Despesa.

***Instituição Remetente***

Os campos do painel Instituição Remetente são automaticamente preenchidos pela aplicação. O nome da Instituição apresentada é sempre aquela, a que o utilizador que está a inserir a fatura, está associado.

pic


***Instituição Devedora***

O painel Instituição Devedora deve ser preenchido com a informação da Instituição competente responsável pela emissão do documento de atestado de Direito.

pic

O utilizador deve primeiro selecionar uma opção na lista de países, conforme figura abaixo. A título de exemplo, de modo a demonstrar o correto preenchimento destes campos, foi utilizado o país Espanha e a Instituição 0700.

pic

Após a seleção do país, o botão **Código Instituição** é exibido ao utilizador, que ao ser selecionado, é apresentada uma janela com a relação de instituições deste país (Espanha).

Nessa janela, a pesquisa pela instituição que consta no documento do atestado de direito, pode ser feita através do código e/ou nome da Instituição.

pic

Para selecionar uma instituição, o utilizador deve:
1. Preencher um dos campos de pesquisa. Exemplo: Código 0700;
2. Selecionar o botão Pesquisar;
3. Clicar sobre a Instituição apresentada no resultado de pesquisa;
4. Clicar no botão Selecionar.

pic

Após a seleção da Instituição, os campos são preenchidos automaticamente, conforma figura abaixo.

pic


***Pedido Individual***

Os campos do painel Pedido Individual servem para identificar o utente no registo da fatura.

pic

O campo “Número Identificação Pessoal” está identificado no atestado de direito apresentado pelo Utente. Deve ser transcrito tal como consta no documento.


***Documento Comprovativo do Direito a Prestação***

Para o preenchimento deste painel, o utilizador deve selecionar o tipo de documento apresentado pelo utente, por exemplo, EHIC, e em seguida preencher o número atribuído a este documento, bem como as respetivas datas (início, quando aplicável e data de termo ou validade).

pic


***Prestação concedida***

O painel Prestação Concedida refere-se às datas de início e fim em que a prestação foi concedida.

pic


***Despesa***

Os campos nesse painel referem-se às despesas com os cuidados de saúde prestados ao doente.

pic

Para o preenchimento deste painel o utilizador deve ter em atenção:
1. "Número Fatura Credor": Número da fatura emitida pela Instituição que prestou os cuidados de saúde;
2. Os campos referentes aos montantes de cuidados médicos, cuidados dentários, medicamentos, hospitalização, cuidados de longa duração e outras prestações devem ser preenchidos quando houver despesa relacionada a algum deles;
3. Quando o campo “Montante de hospitalização” estiver preenchido, os campos “Data de início da hospitalização” e “Data de fim da hospitalização” passam a ser de preenchimento obrigatório;
4. Para inserir uma despesa referente às Outras prestações, o utilizador deve primeiro selecionar uma ou mais opções da lista do campo “Outras prestações” para que no campo “Montante de outras prestações” fique disponível a inserção do valor correspondente.

    ***Nota:** Para selecionar uma opção do campo “outras prestações” basta clicar sobre a opção desejada. Contudo, para desmarcar uma opção selecionada, o utilizador deve pressionar a tecla “Ctrl” no teclado e clicar sobre o item selecionado.*

    ![figModuloRegFatura](img/capitulo5/5_1ModuloRegFatura.png)

    <p class="caption" id="figModuloRegFatura">Teste Identação </p>

5. O campo “Nome ficheiro” deve ser preenchido com uma referência que identifique o registo da fatura e ou um lote de faturas.

     ***Nota:*** *Para selecionar uma opção do campo “outras prestações” basta clicar sobre a opção desejada. Contudo, para desmarcar uma opção selecionada, o utilizador deve pressionar a tecla “Ctrl” no teclado e clicar sobre o item selecionado.* 
     
     <br/>
     
     Para finalizar o processo de introdução de uma nova fatura deve selecionar uma das opções “Voltar” ou “Gravar”:

     ![figVoltarGravar](img/capitulo5/5_1VoltarGravar.png)

     **Voltar:** Caso o utilizador pretenda fechar o formulário de registo de fatura, e não salvar as informações introduzidas,                     deve selecionar a opção “Voltar”. 
   
    **Gravar:** Caso o utilizador pretenda submeter o formulário de registo de fatura gravando assim os dados no sistema, deve selecionar a opção “Gravar”.
      
      a. Se, após a seleção da opção gravar, existirem campos obrigatórios não preenchidos, estes ficam assinalados a vermelho. Serão ainda apresentadas mensagens de erro com a indicação dos campos nos quais devem ser introduzidos valores. 
   
      ![figMsgObrigatorio](img/capitulo5/5_1MsgObrigatorio.png)

      <p class="caption" id="figMsgObrigatorio">Mensagem de Erro "Campos Obrigatórios"</p>
   
      b. Se os campos obrigatórios estiverem corretamente preenchidos e houver problemas na validação do conteúdo de outros campos, a aplicação também irá apresentar mensagens de erro, indicando os campos que precisam ser corrigidos. 
   
      ![figMsgValidacao](img/capitulo5/5_1MsgValidacao.png)
        
      c. Se os campos foram todos preenchidos corretamente e não ocorreu nenhum problema na sua validação, a fatura é guardada no sistema e é apresentada uma mensagem a informar que a fatura foi registada com sucesso.

      ![figMsgSucesso](img/capitulo5/5_1MsgSucesso.png)


<p id="importarFatura"></p>
## 5.2.Módulo Importar Fatura
O módulo de Importar Fatura permite ao utilizador com o perfil EPSNS efetuar a validação e importação de faturas em ficheiro. O utilizador pode aceder a este módulo, na página inicial, ao clicar no seguinte ícone.

![figModuloImpFatura](img/capitulo5/5_2ModuloImpFatura.png)

<p class="caption" id="figModuloImpFatura">Módulo Importar Fatura </p>

O utilizador é então reencaminhado para a página que permite a validação e importação de ficheiros.

<br/>

***Nota:** O processo de importação de faturas é composto por duas fases:*
* Fase 1: Validação;
* Fase 2: Importação.

pic

Antes de iniciar o processo de importação de ficheiros, estes devem passar pelo processo de validação. A seguir estão descritos os processos de validação e importação de ficheiros.

<br/>

***Fase 1: Validar Faturas***

Para realizar o processo de validação de faturas, o utilizador deve carregar no botão “Escolher Ficheiro” (Figura 24) e, de seguida, selecionar o ficheiro que deseja validar.

pic

Com o ficheiro selecionado, carregue no botão “Validar Faturas” (Figura 25) para dar início a validação das faturas que compõem o ficheiro.

pic

Se o processo de validação for concluído sem erros, será apresentada a mensagem “O ficheiro (nome do ficheiro) é válido!” e o resultado deste processo é automaticamente adicionado à tabela desta página. Na demonstração foi utilizado o ficheiro com o nome “FicheiroTeste”. Deste modo, as informações visíveis adicionadas são (Figura 26):
* Data do carregamento: Data em que o ficheiro iniciou o processo de validação;
* Nome do ficheiro: Nome do ficheiro a ser validado;
* Tipo: O E125 refere-se à designação do formulário utilizado para a faturação de migrantes;
* Validação: Este campo é representado por dois ícones.
    * (pic) O ficheiro foi validado com sucesso;
    * (pic) O ficheiro não é váçido e possui erros de validação.
* Estado: Este campo é representado por dois estados.
    * Válido - Ficheiro válido;
    * Erro - Ficheiro com erros.
* Data da importação: A data de importação é apenas preenchida após a importação do ficheiro. Neste momento, o ficheiro apenas foi considerado válido para iniciar a fase de importação.
* Utilizador: Nome do utilizador que realizou esta tarefa.

pic 

***Nota** Concluído o processo de validação com sucesso, o utilizador deve iniciar a segunda fase, identificada por fase de importação.*

<br/>

Se no processo de validação do ficheiro ocorrerem problemas, a mensagem apresentada pela aplicação é “O ficheiro (nome do ficheiro) contem erros de validação. Consulte o relatório, corrija os dados e carregue novamente o ficheiro”. O resultado deste processo também é automaticamente adicionado à tabela desta página (Figura 27).

pic

De modo a apoiar na correção dos erros de validação, a aplicação disponibiliza para o utilizador, um relatório com as mensagens de erro decorrentes do processo de validação, o qual informa quais os campos que não estão a respeitar as regras de validação.

O utilizador pode aceder ao relatório de duas formas:
* **Botão “Consultar Relatório”** – O utilizador deve clicar sobre a linha do ficheiro com erros para que este fique selecionado e carregar no botão Consultar Relatório

pic

A relação dos erros encontrados é apresentada de modo estruturado, sob a forma de uma tabela (Figura 29).

pic

* **Botão “Descarregar Relatório”** - O utilizador deve clicar sobre a linha do ficheiro com erros, para que este fique selecionado, e carregar no botão Descarregar relatório. Será então, feito o download do relatório, ficando guardado no computador do utilizador.

pic

Após aceder ao relatório, o utilizador deve corrigir os erros apresentados e iniciar um novo processo de validação, quantas vezes for necessário, até que o ficheiro seja considerado válido. Pois a aplicação só permite a importação de ficheiros que possuam o estado “Válido”.

<br/>

***Nota**: Os detalhes do relatório de erro, bem como as regras de validação são apresentados no <a href="#">Capítulo 7</a> deste documento.*

<br/>

***Fase 2: Importar Faturas***

Para realizar o processo de importação, o utilizador deve clicar sobre a linha do ficheiro no estado válido, de modo a que este fique selecionado, e em seguida, carregar no botão “Importar” (Figura 31).

pic

Concluído o processo de importação será apresentada ao utilizador a mensagem “A importação foi concluída com sucesso.”, que significa que todas as faturas foram inseridas no FAIT. Desta forma, o processo de importação de faturas por parte do utilizador com o perfil EPSNS, está finalizado.

pic

<p id="consultarRelatorios"></p>
## 5.3.Módulo Consultar Relatórios de Importação
O módulo de Consultar Relatórios de Importação permite ao utilizador com o perfil EPSNS, pesquisar e consultar os relatórios de ficheiros que tiveram problemas durante o processo de importação. O utilizador pode aceder a este módulo, na página inicial, ao clicar no seguinte ícone.

![figModuloConsRelatorio](img/capitulo5/5_3ModuloConsRelatorio.png)

<p class="caption" id="figModuloConsRelatorio">Módulo Consultar Relatórios de Importação </p>

O utilizador é, então, reencaminhado para a página que permite a pesquisa e consulta dos relatórios de importação.

pic

O utilizador poderá pesquisar por relatórios que pertençam à sua entidade, podendo aplicar filtros por nome do ficheiro, semestre e ano.

Os campos “Instituição” e “Estado” são automaticamente preenchidos pelo sistema. A instituição é sempre aquela a que o utilizador está associado. Para pesquisar por um relatório, o utilizador deve selecionar o botão “Pesquisar”.

O utilizador pode optar por utilizar um dos seguintes filtros de pesquisa:
* **Nome do ficheiro** – Deve preencher com o nome do ficheiro que deseja pesquisar;
* **Semestre** - O sistema apresentará, como opções de filtro, os números 1 e 2, que correspondem ao 1º e 2º semestre;
* **Ano** – O utilizador pode selecionar um dos anos apresentados pelo sistema.

Caso não tenha sido aplicado nenhum filtro, a pesquisa devolverá todos os relatórios de importação de ficheiros que tiveram problema no processo de validação da sua instituição.

Após a pesquisa realizada, o utilizador deve clicar sobre a linha do ficheiro, para que este fique selecionado e em seguida, selecionar um dos botões: “Consultar Relatório” ou “Descarregar Relatório”. Assim, fica então disponibilizado o relatório de importação.

pic


<p id="gesFicheirosEPSNS"></p>
## 5.4.Módulo Gestão de Ficheiros
O módulo de Gestão de Ficheiros permite ao utilizador com o perfil EPSNS, pesquisar e consultar o estado dos ficheiros importados da sua instituição. O utilizador pode aceder a este módulo, na página inicial, ao clicar no seguinte ícone.

![figModuloGesFicheiros](img/capitulo5/5_4ModuloGesFicheiros.png)

<p class="caption" id="figModuloGesFicheiros">Módulo Gestão de Ficheiros </p>

O utilizador é, então, reencaminhado para a página que permite a pesquisa e consulta dos ficheiros importados da sua instituição.

<p id="gesFaturasEPSNS"></p>
## 5.5.Módulo Gestão de Faturas
O módulo de Gestão de Faturas permite ao utilizador com o perfil EPSNS, pesquisar, consultar e editar faturas de ficheiros importados da sua instituição. O utilizador pode aceder a este módulo, na página inicial, ao clicar no seguinte ícone.


![figModuloGesFaturas](img/capitulo5/5_5ModuloGesFaturas.png)

<p class="caption" id="figModuloGesFaturas">Módulo Gestão de Faturas </p>

O utilizador é então reencaminhado para a página que permite a pesquisa, consulta e edição de faturas da sua instituição
