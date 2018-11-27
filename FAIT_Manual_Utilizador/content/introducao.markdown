---
layout: default
title: "Introdução"
---

<p id="sobre-este-manual"></p>
# 1. Sobre este Manual

Este manual tem como objetivo auxiliar os diferentes utilizadores a compreenderem melhor o funcionamento da aplicação FAIT - Faturação de Acordos Internacionais e Transfronteiriços. 
O manual está organizado em vários capítulos:

1. **Sobre este Manual** - o capítulo presente, que faz uma breve descrição dos capítulos seguintes, nos quais pode ser encontrada a informação de que o utilizador precisa.

2. **Tabela de Acrónimos, termos e definições** - contém todos os acrónimos utilizados ao longo do manual.   

3. **Enquadramento** - neste capítulo é apresentado o sistema FAIT e os objetivos.

4. **Conceitos Básicos** - são explicados os principais conceitos que suportam a aplicação, incluindo os seguintes subcapítulos:

   * Aceder ao FAIT, onde é descrito como é que os utilizadores devem aceder ao sistema; Alteração da Palavra-Passe, onde o utilizador pode perceber como se muda a palavra-passe.

   * Permissões e Perfis, no qual são descritos os diferentes tipos de utilizadores previstos no FAIT, bem como as permissões que lhes poderão ser associadas.

5. **Módulos Perfil EPSNS** – neste capítulo o utilizador visualiza um conjunto de módulos, onde poderá efetuar todas as ações à que possui permissão, incluindo os seguintes subcapítulos:

   * Módulo Registar Fatura;

   * Módulo Importar Fatura;

   * Módulo Consultar Relatórios de Importação;

   * Módulo Gestão de Ficheiros;

   * Módulo Gestão de Faturas.

6. **Módulos Perfil ACSS** - neste capítulo o utilizador visualiza um conjunto de módulos, onde poderá efetuar todas as ações à que possui permissão, incluindo os seguintes subcapítulos:

   * Módulo Gestão de Ficheiros

   * Módulo Gestão de Faturas

7. **Regras de Validação** - neste capítulo serão explicadas as regras de validação implementadas onde servem para validar toda a informação contida no ficheiro, tanto no que diz respeito ao seu conteúdo, mas também quanto a sua estrutura.

8. **Mapeamento do ficheiro** – é explicado o que é necessário para que a importação do ficheiro ocorra com sucesso. Inclui os subcapítulos:

   * Mapeamento da última linha do Ficheiro

   * Representação do mapeamento de uma fatura no Ficheiro

   * Representação do mapeamento da última linha do Ficheiro

9. **Regras de Negócio** – neste capítulo é foi disponibilizada informação que o utilizador poderá consultar sobre o negócio.

10. **Apoio ao Utilizador** - neste capítulo o utilizador é informado como poderá contactar a equipa de suporte á aplicação, caso surjam dúvidas, dificuldades bem como sugestões de melhorias.

11. **Controlo do Documento** - neste capítulo é identificado o histórico de alterações.


<p id="tabela-de-acrnimos"></p>
# 2. Tabela de Acrónimos, termos e definições

Na tabela seguinte estão apresentadas a siglas, ordenadas por ordem alfabética, que serão utilizadas no manual e na aplicação.

|  Sigla |  Designação             |           
|--------|-------------------------|
|  ACSS  |  Administração Central do Sistema de Saúde |           
|  EPSNS |  Entidades Prestadoras do SNS |           
|  SIGAI |  Sistema de Informação para a Gestão de Acordos Internacionais |           
   
 
<p id="termos-e-definies"></p>
# 3. Enquadramento

O presente documento contém a informação necessária para a compreensão das funcionalidades existentes no âmbito do desenvolvimento da validação da Faturação de Acordos Internacionais e Transfronteiriços – FAIT.

As funcionalidades foram desenvolvidas para responder à necessidade de validação da informação enviada pelas Entidades Prestadoras de Cuidados de Saúde referente à faturação das despesas com cuidados de saúde dos segurados de outro Estado-Membro ou de país terceiro com o qual Portugal tenha Acordo Bilateral e que para o efeito tenham apresentado um documento de atestado de direito válido.
O ambiente de execução aplicacional é totalmente baseado e orientado às tecnologias Web, isto é, serão desenvolvidos utilizando a tecnologia Apache Wicket, assegurando que os utilizadores finais podem realizar todas as interações com o sistema através do seguinte browser web:

* Google Chrome;

Todas as comunicações ao nível da camada de aplicação do Modelo OSI (Open System Interconnection) são realizadas tirando partido do protocolo HTTP/HTTPS.
O manual apresenta as funcionalidades separadas por tipo de perfil (ACSS e EPSNS) e orienta quanto às regras de validação da informação da faturação dessas despesas, para posterior importação para a área de Despesas Efetivas na vertente de Portugal Credor no SIGAI.


<p id="conceitos-bsicos"></p>
# 4. Conceitos Básicos

Associada à interação com o sistema existe um conjunto de conceitos para os quais é chamada a atenção neste capítulo. 
Quer a importação dos ficheiros, ou formulários que permitem a criação ou edição de dados têm um conjunto de regras de negócio e validações para facilitar o preenchimento correto dos dados. Para auxiliar as validações existem 4 tipos de mensagens:


* **Mensagem de Informação**: Representada pelo ícone <img alt="logo" src="img/capitulo4/InfoIcon.png"> . Tem por objetivo apenas informar ao utilizador.


* **Mensagem de Alerta**: Representada pelo ícone <img alt="logo" src="img/capitulo4/alertIcon.png"> . Seu objetivo passa por alertar o utilizador sobre algo. Este tipo de mensagem não impede que o utilizador execute uma ação.


* **Mensagem de Erro**: Representada pelo ícone <img alt="logo" src="img/capitulo4/ErroIcon.png"> . Este tipo de mensagem informa ao utilizador que ocorreu algum problema durante a execução de uma ação, e impede que esta ação seja executada até que o problema seja corrigido.


* **Mensagem de Sucesso**: Representada pelo ícone <img alt="logo" src="img/capitulo4/SucessIcon.png"> . Apenas informa ao utilizador que a sua ação foi executada com sucesso.


No cabeçalho das páginas do **FAIT** existe um conjunto de dados que pretende informar e contextualizar o utilizador: 

*	Nome do utilizador;
*	Nome da entidade prestadora associada ao utilizador;
*	Botão das opções avançadas. Ao clicar neste, o utilizador tem acesso a opção de alterar a sua palavra-passe.


<div id="aceder-ao-fait"></div>
<h2 id="41-aceder-ao-fait">4.1. Aceder ao FAIT</h2>

O acesso ao FAIT é realizado através da navegação ao endereço em [https://fait.min-saude.pt/](https://fait.min-saude.pt/) num *browser* de internet.
Ao aceder à plataforma FAIT irá surgir a página que aparece na figura abaixo. 

![figLogin](img/capitulo4/4_1Login.png)

<p class="caption" id="figLogin">Página de acesso do FAIT </p>


O utilizador deve, nesta página, inserir as suas credenciais de acesso (Nome de utilizador e palavra-passe), e clicar no botão **Avançar**.

Se o utilizador com o perfil EPSNS possuir mais de uma instituição associada ao seu perfil, é-lhe solicitado que escolha a instituição que pretende entrar em sessão. Caso o utilizador tenha apenas uma Instituição associada será estabelecida a sessão automaticamente.

![figLoginInst](img/capitulo4/4_1LoginInst.png)

<p class="caption" id="figLoginInst">Selecionar Instituição</p>

* **Novo utilizador**
Para que um novo utilizador tenha acesso a aplicação, deve solicitar à equipa de suporte da SPMS, via [servicedesk@spms.min-saude.pt](servicedesk@spms.min-saude.pt), indicando o nome da aplicação do assunto do email [FAIT]. O email deve conter as seguintes informações:

•	Nome de Utilizador;
•	Email;
•	Instituição que pertence
O utilizador receberá um email da equipa de suporte com os dados da nova credencial de acesso.

* **Alterar Senha**
A aplicação permite que o utilizador altere a sua própria palavra passe, a qualquer momento. Ao carregar no botão das opções avançadas logo, situado no canto superior direito da página, surgirá a opção “Alteração de Senha”.

![figRecPass](img/capitulo4/4_1RecPass1.png)

<p class="caption" id="figRecPass">Alterar palavra-passe</p>

Após clicar em **Alterar palavra-passe** da Senha é apresentada a seguinte página de alteração da password:

![figRecPass](img/capitulo4/4_1RecPass2.png)

<p class="caption" id="figRecPass">Página para alterar a palavra-passe</p>


O utilizador deve preencher todos os campos e clicar no botão **Alterar**.

* **Recuperar Senha**
Se por qualquer motivo, o utilizador precisar de uma nova senha deverá clicar em **Recuperar Senha** e preencher o campo do formulário, com o nome do utilizador, conforme a figura abaixo e clicar em **Enviar**. 

![figRecPass](img/capitulo4/4_1RecPass3.png)

<p class="caption" id="figRecPass">Recuperação de senha</p>

Após a submissão do pedido de recuperação de senha, o utilizador receberá, no email associado ao nome de utilizador submetido, as instruções para reposição da palavra-passe.

* **Terminar Sessão**
O utilizador pode sair do sistema a qualquer momento. Para tal, deve clicar no botão Terminar Sessão, representado pelo ícone <img alt="logo" src="img/capitulo4/4_1SessionIcon.png"> , situado no campo superior direito da página. 


\* Só será possível recuperar a senha indicando o endereço eletrónico se este estiver associado apenas a um utilizador.

Junto ao logotipo do SGES, encontra-se o botão de atalho para os diferentes menus [](#figatalho_menu). Este botão permite ao utilizador, em qualquer momento na navegação, mudar para um determinado menu.

![figatalho_menu](img/pages/5_1_3_2.JPG)

<p class="caption" id="figatalho_menu"> Botão de atalho para os diferentes menus destacado a amarelo e a janela mostrada quando se carrega no referido botão. </p> 

Na primeira vez que o utilizador acede à aplicação, aparecerá a página de ([5.2. Alteração da senha](#alterao-da-senha)).  

<p id="alteracao-de-senha"></p>
## 4.2. Alteração da senha

A qualquer momento, o utilizador pode fazer a alteração da sua senha, clicando no botão das opções avançadas situado no canto superior direito da página ~[4.Conceitos Básicos](#conceitos-bsicos). 
Após clicar em **Alterar Password** é apresentada uma página de alteração de senha, [](#figAlteracaoSenha). O utilizador deverá inserir os campos obrigatórios ( ver tabela abaixo e [](#figAlteracaoSenha).

|    |  Campos Obrigatórios                   |           
|----|----------------------------------------|
| a) |  Senha utilizada atualmente            | 
| b) |  Nova senha pretendida                 |  
| c) |  Repetição da senha pretendida         |

Após o preenchimento dos campos, o utilizador deverá finalizar a alteração clicando em **Alterar**.

![figAlteracaoSenha](img/pages/5_2_1.jpg)

<p class="caption" id="figAlteracaoSenha"> Página de alteração de senha </p>

<p id="pgina-de-pesquisa"></p>
## 4.3. Gestão de utilizadores
<p id="gestaoUtilizadores"></p>

O utilizador tiver o perfil de administrador (ARS_ADMIN ou ADMIN_ENTIDADE), pode criar/gerir utilizadores para atualizarem os diferentes painéis no SGES na entidade respetiva.
É possível criar utilizadores com os seguintes perfis:

* **SGES_ENTIDADE** - Os utilizadores com este perfil poderão executar as operações sobre a *entidade* assim como criar e alterar *estabelecimentos*;

* **SGES_EQUIPAMENTOS** - Os utilizadores com este perfil poderão executar as operações sobre os *equipamentos* médicos pesados e sobre a *produção* dos mesmos;

* **SGES_INSTALACOES** - Os utilizadores com este perfil poderão executar as operações sobre as *instalações* de cada estabelecimento médico.

Para criar novos utilizadores, o utilizador deve clicar no botão das opções avançadas situado no canto superior direito da página 
([](#conceitos-bsicos)). Após clicar em **Gestão de Utilizadores**, aparecerá a página de **Gestão de Utilizadores** [](#figGestaoUtilizadores).

![figGestaoUtilizadores](img/pages/5_4_1.jpg)

<p class="caption" id="figGestaoUtilizadores"> Gestão de utilizadores </p>

O utilizador deve clicar em **Criar**, para aparecer a página de *Criar Utilizador* [](#figCriarUtilizador).

![figCriarUtilizador](img/pages/5_4_2.jpg)

<p class="caption" id="figCriarUtilizador"> Criar utilizador </p>

Para a criação de um utilizador devem ser preenchidos os seguintes campos obrigatórios:

|    |  Campos Obrigatórios [](#figCriarUtilizador)  | |    
|----|----------------------------------------|----|
| a) |  Nome       		                ||
| b) |  BI/CC                           ||
| c) |  Data de nascimento              ||
| d) |  Sexo                            ||
| e) |  E-mail                          ||
| f) |  Perfil                          | SGES_ENTIDADE|
| |                                     | SGES_EQUIPAMENTOS|

No final da edição o utilizador para gravar as alterações deve clicar no botão **GUARDAR**. Após clicar irá ser notificado com o resultado da operação.

No SGES podem ainda existir utilizadores com outros perfis. No subcapítulo [16.2 Perfis e respetivas permissões ](#listaperfis) é possível consultar a lista de perfis, e respetivas permissões, disponíveis no SGES.

<p id="natureza-juridica"></p>
## 4.4. Natureza jurídica e os seus campos
As entidades públicas - ULS, Centros Hospitalares e Hospitais do SNS - têm acesso a informações relativas a entidades, estabelecimentos,equipamentos e instalações (ver capítulos 6 a 14 inclusive).

Informações relativas a Acordos/Convenções são acedidas, exclusivamente, pelas ARSs ACSS (ver capítulo 15).

<p id="home"></p>
## 5. Menu Principal

Uma vez identificado e autenticado, é apresentado ao utilizador o menu principal do SGES onde pode aceder às diferentes funcionalidades que lhe estão disponíveis consoante o seu perfil; caso o utilizador tenha o perfil de administração de uma entidade pública o menu principal será o mostrado na [](#figura_menu_ADMIN_entidade).

![figura_menu_ADMIN_entidade](img/pages/5_1_3.JPG)

<p class="caption" id="figura_menu_ADMIN_entidade"> Menu Principal para um utilizador com o perfil de administrador de uma entidade pública. </p>
