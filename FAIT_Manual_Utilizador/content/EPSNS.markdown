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
* 1 - Preencher um dos campos de pesquisa. Exemplo: Código 0700;
* 2 - Selecionar o botão Pesquisar;
* 3 - Clicar sobre a Instituição apresentada no resultado de pesquisa;
* 4 - Clicar no botão Selecionar.

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
* 1 - "Número Fatura Credor": Número da fatura emitida pela Instituição que prestou os cuidados de saúde;
* 2 - Os campos referentes aos montantes de cuidados médicos, cuidados dentários, medicamentos, hospitalização, cuidados de longa duração e outras prestações devem ser preenchidos quando houver despesa relacionada a algum deles;
* 3 - Quando o campo “Montante de hospitalização” estiver preenchido, os campos “Data de início da hospitalização” e “Data de fim da hospitalização” passam a ser de preenchimento obrigatório;
* 4 -  Para inserir uma despesa referente às Outras prestações, o utilizador deve primeiro selecionar uma ou mais opções da lista do campo “Outras prestações” para que no campo “Montante de outras prestações” fique disponível a inserção do valor correspondente.
***Nota:** Para selecionar uma opção do campo “outras prestações” basta clicar sobre a opção desejada. Contudo, para desmarcar uma opção selecionada, o utilizador deve pressionar a tecla “Ctrl” no teclado e clicar sobre o item selecionado. *

pic

* 5 - O campo “Nome ficheiro” deve ser preenchido com uma referência que identifique o registo da fatura e ou um lote de faturas.
      ***Nota:*** _*Para selecionar uma opção do campo “outras prestações” basta clicar sobre a opção desejada. Contudo, para desmarcar uma opção selecionada, o utilizador deve pressionar a tecla “Ctrl” no teclado e clicar sobre o item selecionado.*_
      
Para finalizar o processo de introdução de uma nova fatura, deve selecionar uma das opções “Voltar” ou “Gravar”:

pic


<p id="importarFatura"></p>
## 5.2.Módulo Importar Fatura
O módulo de Importar Fatura permite ao utilizador com o perfil EPSNS efetuar a validação e importação de faturas em ficheiro. O utilizador pode aceder a este módulo, na página inicial, ao clicar no seguinte ícone.

![figModuloImpFatura](img/capitulo5/5_2ModuloImpFatura.png)

<p class="caption" id="figModuloImpFatura">Módulo Importar Fatura </p>

O utilizador é então reencaminhado para a página que permite a validação e importação de ficheiros.

***Nota:** O processo de importação de faturas é composto por duas fases:*
* Fase 1: Validação;
* Fase 2: Importação.




<p id="consultarRelatorios"></p>
## 5.3.Módulo Consultar Relatórios de Importação
O módulo de Consultar Relatórios de Importação permite ao utilizador com o perfil EPSNS, pesquisar e consultar os relatórios de ficheiros que tiveram problemas durante o processo de importação. O utilizador pode aceder a este módulo, na página inicial, ao clicar no seguinte ícone.

![figModuloConsRelatorio](img/capitulo5/5_3ModuloConsRelatorio.png)

<p class="caption" id="figModuloConsRelatorio">Módulo Consultar Relatórios de Importação </p>

O utilizador é, então, reencaminhado para a página que permite a pesquisa e consulta dos relatórios de importação.

<p id="gesFicheirosEPSNS"></p>
## 5.4.Módulo Gestão de Ficheiros
O módulo de Gestão de Ficheiros permite ao utilizador com o perfil EPSNS, pesquisar e consultar o estado dos ficheiros importados da sua instituição. O utilizador pode aceder a este módulo, na página inicial, ao clicar no seguinte ícone.

![figModuloGesFicheiros](img/capitulo5/5_4ModuloGesFicheiros.png)

<p class="caption" id="figModuloGesFicheiros">Módulo Gestão de Ficheiros </p>

O utilizador é, então, reencaminhado para a página que permite a pesquisa e consulta dos
ficheiros importados da sua instituição.

<p id="gesFaturasEPSNS"></p>
## 5.5.Módulo Gestão de Faturas
O módulo de Gestão de Faturas permite ao utilizador com o perfil EPSNS, pesquisar, consultar e editar faturas de ficheiros importados da sua instituição. O utilizador pode aceder a este módulo, na página inicial, ao clicar no seguinte ícone.


![figModuloGesFaturas](img/capitulo5/5_5ModuloGesFaturas.png)

<p class="caption" id="figModuloGesFaturas">Módulo Gestão de Faturas </p>

O utilizador é então reencaminhado para a página que permite a pesquisa, consulta e edição de faturas da sua instituição
