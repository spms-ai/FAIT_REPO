---
layout: default
title: "ACSS"
---

<p id="ACSS"></p>
# 5. Módulos Perfil ACSS
O utilizador associado ao perfil ACSS, após efetuar o login à plataforma FAIT (Capítulo 4.1), visualiza um conjunto de módulos, onde poderá efetuar todas as ações a que possui permissão.

![figModulosACSS](img/capitulo6/Modulos.png)

<p class="caption" id="figModulosASS">Módulos Perfil ACSS </p>


<p id="gesFicheirosACSS"></p>
## 6.1.Módulo Gestão de Ficheiros
O módulo de Gestão de Ficheiros permite ao utilizador com o perfil ACSS, pesquisar, consultar, integrar, não integrar e validar os ficheiros importados de todas as Entidades Prestadoras do SNS registadas no sistema. O utilizador pode aceder a este módulo, na página inicial, ao clicar no seguinte ícone.

![figModuloGesFicheirosACSS](img/capitulo6/6_1ModuloGesFicheiros.png)

<p class="caption" id="figModuloGesFicheirosACSS">Módulo Gestão de Ficheiros </p>

O utilizador é então reencaminhado para a página que permite a pesquisa e consulta dos ficheiros importados.

![figPaginaGesFicheirosACSS](img/capitulo6/6_1PaginaGesFicheiros.png)

<p class="caption" id="figPaginaGesFicheirosACSS">Página de Gestão de Ficheiros </p>

O utilizador poderá pesquisar por ficheiros que pertençam a qualquer entidade registada no sistema, podendo aplicar filtros por Nome Ficheiro, Estado, Semestre, Instituição e Ano.

Para pesquisar por um ficheiro, o utilizador deve selecionar o botão “Pesquisar”.

O utilizador pode optar por utilizar os seguintes filtros de pesquisa:
* **Nome do ficheiro** – Corresponde ao nome do ficheiro;
* **Instituição** - O sistema per sistema permite a pesquisa por nome ou código da instituição. Este filtro de pesquisa é _autocomplete_, ou seja, à medida que o utilizador insere uma letra ou número, o sistema fornece automaticamente a lista de instituições registadas que contém no seu nome ou código, o caracter correspondente ao introduzido (Figura 50).

![figFiltroPesquisaInst](img/capitulo6/6_1FiltroPesquisaInst.png)

<p class="caption" id="figFiltroPesquisaInst">Filtro de Pesquisa "Instituição"</p>

* **Estado** – O sistema apresentará, como opções de filtro, os estados:
    * Válido - O fihceiro está válido para ser integrado no SIGAI;
    * Integrado - O ficheiro já foi integrado no SIGAI;   
    * Não Integrado - O ficheiro não será integrado no SIGAI.   
* **Semestre** - O sistema apresentará, como opções de filtro, os números 1 e 2, que correspondem ao 1º e 2º semestre;
* **Ano** – O utilizador pode selecionar um dos anos apresentados pelo sistema.

Caso não tenha sido aplicado nenhum filtro, a pesquisa devolverá todos os ficheiros importados no sistema. Se após o preenchimento de pelo menos um dos campos de pesquisa, não houver registos no sistema correspondentes aos critérios pesquisados, é apresentada uma mensagem de “Não foram encontrados registos com os critérios de procura inseridos”, conforme figura abaixo.

pic

Através da tabela de resultados da pesquisa do ficheiro, o utilizador visualiza a Ref. CLA, que corresponde ao ficheiro que a fatura está inserida, a Instituição credora, o ano, o semestre, o estado, o número de faturas e o montante total das mesmas, bem como o número e o montante total de faturas não integradas no ficheiro. 

pic

Apenas o utilizador com o perfil ACSS tem permissões para “Integrar”, “Não Integrar” e “Validar” ficheiros.

***Não Integrar Ficheiro***

Essa funcionalidade permite ao utilizador com o perfil ACSS, decidir se um ficheiro não deve ser integrado nas Despesas Efetivas do SIGAI. Para realizar esta ação, o utilizador deve clicar sobre a linha do ficheiro na tabela de resultados para que este fique selecionado, e carregar no botão “Não Integrar”. Esta opção encontra-se ativa apenas para ficheiros com o estado designado “Válido”.

pic

Ao selecionar o botão “Não Integrar”, é apresentado um _pop-up_ de pedido de confirmação da não integração do ficheiro selecionado no SIGAI.

pic

Caso confirme, selecionando a opção “Sim”, o ficheiro assumirá o estado “Não integrado” e as faturas do ficheiro, o estado “Não integrada”. O sistema também apresenta uma mensagem “O ficheiro (nome do ficheiro) não será integrado no SIGAI”. Caso selecione a opção “Não”, retornará à página de pesquisa.

pic

***Validar Ficheiro***

Esta funcionalidade permite ao utilizador com o perfil ACSS decidir se um ficheiro no estado “não integrado” deve novamente ser considerado “válido”, para integrar nas Despesas Efetivas do SIGAI. Para realizar esta ação, o utilizador deve clicar sobre a linha do ficheiro pretendido na tabela de resultados para que este fique selecionado, e carregar no botão “Validar”. Esta opção encontra-se ativa apenas para ficheiros com o estado “Não Integrado”.

pic

Ao selecionar o botão “Validar” é apresentado um pop-up de pedido de confirmação da validação do ficheiro selecionado.

pic

Caso confirme, selecionando a opção “Sim”, o ficheiro assumirá o estado “Válido” e as faturas do ficheiro, o estado “Válida”. O sistema também irá apresentar uma mensagem “O ficheiro (nome do ficheiro) é válido e as faturas válidas”. Caso selecione a opção “Não”, retornará à página de pesquisa.

pic (57)

***Integrar Ficheiro***

Esta funcionalidade permite ao utilizador com o perfil ACSS decidir se um ficheiro no estado válido deve ser integrado nas Despesas Efetivas do SIGAI. Para realizar esta ação, o utilizador deve clicar sobre a linha do ficheiro pretendido na tabela de resultados, para que este fique selecionado, e carregar no botão “Integrar”. Esta opção encontra-se ativa apenas para ficheiros com o estado “Válido”.

pic

Ao selecionar o botão “Integrar” é apresentado um pop-up de pedido de confirmação da integração do ficheiro selecionado no SIGAI. 

pic

Caso confirme, selecionando a opção “Sim”, todas as faturas incluídas no ficheiro serão integradas nas Despesas Efetivas do SIGAI, o ficheiro assumirá o estado “Integrado” e as faturas, o estado “Integrada”. O sistema também irá apresentar uma mensagem “O ficheiro (nome do ficheiro) foi integrado com sucesso”. Caso selecione a opção “Não”, retornará à página de pesquisa.

pic


<p id="gesFaturasACSS"></p>
## 6.2.Módulo Gestão de Faturas
O módulo de Gestão de Faturas permite ao utilizador com o **perfil ACSS**, pesquisar, consultar, editar, integrar, não integrar e validar as faturas importadas ou registadas no sistema. O utilizador pode aceder a este módulo, na página inicial, ao clicar no seguinte ícone.

![figModuloGesFaturasACSS](img/capitulo6/6_2ModuloGesFaturas.png)

<p class="caption" id="figModuloGesFaturasACSS">Módulo Gestão de Faturas </p>

O utilizador é então reencaminhado para a página que permite a pesquisa, consulta, edição, integração, não integração e validação de faturas.

![figPaginaGesFaturasACSS](img/capitulo6/6_2PaginaGesFaturas.png)

<p class="caption" id="figPaginaGesFaturasACSS">Página de Gestão de Faturas </p>

O utilizador poderá pesquisar quaisquer faturas, podendo aplicar filtros por Nome Ficheiro, Estado, Fatura IC, País, Instituição, Ano, Semestre e Nome.

Para pesquisar por uma fatura, o utilizador deve selecionar o botão “Pesquisar”.

O utilizador pode optar por utilizar os seguintes filtros de pesquisa:
* **Nome do ficheiro** – Corresponde ao nome do ficheiro;
* **Instituição** - O sistema per sistema permite a pesquisa por nome ou código da instituição. Este filtro de pesquisa é _autocomplete_, ou seja, à medida que o utilizador insere uma letra ou número, o sistema fornece automaticamente a lista de instituições registadas que contém no seu nome ou código, o caracter correspondente ao introduzido (Figura 63).

![figFiltroPesquisaInst2](img/capitulo6/6_2FiltroPesquisaInst.png)

<p class="caption" id="figFiltroPesquisaInst2">Filtro de Pesquisa "Instituição" </p>

* **Estado** – O sistema apresentará, como opções de filtro, os estados:
    * Válida - A fatura é válida para ser integrada no SIGAI;
    * Integrada - A fatura já foi integrada no SIGAI;   
    * Não Integrada - A fatura não será integrada no SIGAI.   
* **Fatura IC** - Corresponde ao número de fatura atribuído pela Instituição;
* **País** - Corresponde ao país responsável pelo documento de Atestado de Direito. O utilizador pode selecionar um dos países apresentado pelo sistema;
* **Semestre** - O sistema apresentará, como opções de filtro, os números 1 e 2, que correspondem ao 1º e 2º semestre;
* **Ano** – O utilizador pode selecionar um dos anos apresentados pelo sistema;
* **Nome** - Corresponde ao nome da pessoa que recebeu os cuidados de saúde.

Caso não tenha sido aplicado nenhum filtro, a pesquisa devolverá todas as faturas registadas ou importadas no sistema. Se após o preenchimento de pelo menos um dos campos de pesquisa, não houver registos no sistema correspondentes aos critérios pesquisados, é apresentada uma mensagem de “Não foram encontrados registos com os critérios de procura inseridos”, conforme figura abaixo.

pic

Através da tabela de resultados da pesquisa de faturas, o utilizador consegue visualizar o estado atual da fatura, como também, o nome e número de identificação pessoal do Segurado e o montante total da mesma.

pic

***Consultar Faturas***

Para visualizar uma fatura, o utilizador deve clicar sobre a linha da fatura para que esta fique selecionada, e carregar no botão “Consultar”.

pic

Em seguida, é apresentado o formulário da fatura selecionada, conforme imagem abaixo.

pic

A opção “Consultar” apenas apresenta os dados do formulário da fatura em questão, sob a forma de consulta, não sendo permitida a alteração em nenhum dos seus campos.

Deve selecionar a opção “Voltar” para fechar o formulário, e retomar à pesquisa anteriormente efetuada.

***Editar Faturas***

Para editar uma fatura, o utilizador deve clicar sobre a linha da fatura para que esta fique selecionada e carregar no botão “Editar”. Esta opção encontra-se ativa apenas para faturas com o estado “Válida”.

pic

Em seguida, é apresentado o formulário da fatura selecionada.

pic 

O sistema permite ao utilizador com o perfil ACSS, a edição de todos os campos das faturas importadas ou registadas no sistema, desde que essas faturas possuam o estado “Válida”.

Para finalizar o processo de edição de uma fatura, deve selecionar uma das opções “Cancelar” ou “Alterar”:
