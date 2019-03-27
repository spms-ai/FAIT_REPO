
<div id="sobre-este-manual">
</div>
<br>

<h1 id="1-sobre-este-manual">
 1. Sobre este Manual
</h1>

<p>Este manual tem como objetivo auxiliar os diferentes utilizadores a compreenderem melhor o funcionamento da aplicação FAIT - Faturação de Acordos Internacionais e Transfronteiriços. </p>
<p>O manual está organizado em vários capítulos:</p>

<p>
</p>

<ol>
	<li>
		<strong><a href="#sobre-este-manual">Sobre este Manual</a></strong> - o capítulo presente, que faz uma breve descrição dos capítulos seguintes, nos quais pode ser encontrada a informação de que o utilizador precisa;<br>
	</li>

	<li>
		<strong><a href="#tabela-de-acrnimos">Tabela de Acrónimos</a></strong> - contém todos os acrónimos utilizados ao longo do manual;<br>
	</li>
	<li>
		<strong><a href="#introduo">Enquadramento</a></strong> - neste capítulo é apresentado o sistema FAIT e os objetivos;	<br>
	</li>
	<li>
		<strong><a href="#conceitos-bsicos">Conceitos Básicos</a></strong> - são explicados os principais conceitos que suportam a aplicação, incluindo os seguintes subcapítulos:
		<ul>
			<li>
				<a href="#aceder-ao-fait">Aceder ao FAIT</a>, onde é descrito como é que os utilizadores devem aceder ao sistema; Alteração da Palavra-Passe, onde o utilizador pode perceber como se muda a palavra-passe;
			</li>

			<li>
				<a href="#permissoesPerfis">Permissões e Perfis</a>, no qual são descritos os diferentes tipos de utilizadores previstos no FAIT, bem como as permissões que lhes poderão ser associadas;
			</li>

			<li>
				<a href="#alteraPass">Alteração da Senha</a>, onde o utilizador pode perceber como se muda a <em>password</em>.
			</li>
		</ul>
	</li>

	<li>
		<strong><a href="#sobre-este-manual">Módulos Perfil EPSNS</a></strong> - neste capítulo o utilizador visualiza um conjunto de módulos, onde poderá efetuar todas as ações à que possui permissão, incluindo os seguintes subcapítulos:<br>
		<ul>
			<li>
				<a href="#RegistarFatura">Módulo Registar Fatura;</a>
			</li>
			<li>
				<a href="#RegistarFatura">Módulo Importar Fatura;</a>
			</li>
			<li>
				<a href="#RegistarFatura">Módulo Consultar Relatórios de Importação;</a>
			</li>
			<li>
				<a href="#RegistarFatura">Módulo Gestão de Ficheiros;</a>
			</li>
			<li>
				<a href="#RegistarFatura">Módulo Gestão de Faturas.</a>
			</li>
		</ul>
	</li>
	<li>
		<strong><a href="#ModulosACSS">Módulos Perfil ACSS</a></strong> - neste capítulo o utilizador visualiza um conjunto de módulos, onde poderá efetuar todas as ações à que possui permissão, incluindo os seguintes subcapítulos:<br>
		<ul>
			<li>
				<a href="#RegistarFatura">Módulo Gestão de Ficheiros;</a>
			</li>
			<li>
				<a href="#RegistarFatura">Módulo Gestão de Faturas</a>
			</li>
		</ul>
	</li>
	<li>
		<strong><a href="#RegrasValidacao">Regras de Validação</a></strong> - neste capítulo serão explicadas as regras de validação implementadas onde servem para validar toda a informação contida no ficheiro, tanto no que diz respeito ao seu conteúdo, mas também quanto a sua estrutura.<br>
	</li>
	<li>
		<strong><a href="#MapFicheiro">Mapeamento do ficheiro</a></strong> - é explicado o que é necessário para que a importação do ficheiro ocorra com sucesso. Inclui os subcapítulos:<br>
		<ul>
			<li>
				<a href="#MapUltimaLinha">Mapeamento da última linha do Ficheiro;</a>
			</li>
			<li>
				<a href="#RepresFatura">Representação do mapeamento de uma fatura no Ficheiro</a>
			</li>
			<li>
				<a href="#RepresUltimaLinha">Representação do mapeamento da última linha do Ficheiro</a>
			</li>
		</ul>
	</li>
	<li>
		<strong><a href="#RegrasNegocio">Regras de Negócio</a></strong> - neste capítulo é foi disponibilizada informação que o utilizador poderá consultar sobre o negócio.<br>
	</li>
	<li>
		<strong><a href="#ApoioUt">Apoio ao Utilizador</a></strong> - neste capítulo o utilizador é informado como poderá contactar a equipa de suporte á aplicação, caso surjam dúvidas, dificuldades bem como sugestões de melhorias.<br>
	</li>
		<li>
	<strong><a href="#ControlDocu">Controlo do Documento</a></strong> - neste capítulo é identificado o histórico de alterações.<br>
	</li>
</ol>


<hr>
<div id="tabela-de-acrnimos"></div><br>
<br>
<br>
<h1 id="2-tabela-de-acrónimos">2. Tabela de Acrónimos</h1>
<p>A tabela seguinte contém a descrição de várias siglas usadas ao longo do documento.</p>
<table>
	<thead>
		<tr>
			<th><h5>Sigla</h5></th>
			<th><h5>Designação</h5></th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td style="border-bottom: 1pt solid rgb(0, 80, 130); border-top: 1pt solid rgb(0, 80, 130);; border-right: 1pt solid rgb(0, 80, 130);; border-left: 1pt solid rgb(0, 80, 130);">ACSS</td>
			<td style="border-bottom: 1pt solid rgb(0, 80, 130); border-top: 1pt solid rgb(0, 80, 130);; border-right: 1pt solid rgb(0, 80, 130);; border-left: 1pt solid rgb(0, 80, 130);">Administração Central do Sistema de Saúde</td>
		</tr>
		<tr>
			<td style="border-bottom: 1pt solid rgb(0, 80, 130); border-top: 1pt solid rgb(0, 80, 130);; border-right: 1pt solid rgb(0, 80, 130);; border-left: 1pt solid rgb(0, 80, 130);">EPSNS</td>
			<td style="border-bottom: 1pt solid rgb(0, 80, 130); border-top: 1pt solid rgb(0, 80, 130);; border-right: 1pt solid rgb(0, 80, 130);; border-left: 1pt solid rgb(0, 80, 130);">Entidade Prestadora do SNS</td>
		</tr>
		<tr>
			<td style="border-bottom: 1pt solid rgb(0, 80, 130); border-top: 1pt solid rgb(0, 80, 130);; border-right: 1pt solid rgb(0, 80, 130);; border-left: 1pt solid rgb(0, 80, 130);">SIGAI</td>
			<td style="border-bottom: 1pt solid rgb(0, 80, 130); border-top: 1pt solid rgb(0, 80, 130);; border-right: 1pt solid rgb(0, 80, 130);; border-left: 1pt solid rgb(0, 80, 130);">Sistema de Informação para a Gestão de Acordos Internacionais</td>
		</tr>
	</tbody>
</table>

<hr>
<div id="termos-e-definies"></div>
<br>
<br>
<h1 id="termos-e-definies">3. Enquadramento</h1>

<p>O presente documento contém a informação necessária para a compreensão das funcionalidades existentes no âmbito do desenvolvimento da validação da Faturação de Acordos Internacionais e Transfronteiriços – FAIT.</p>

<p>As funcionalidades foram desenvolvidas para responder à necessidade de validação da informação enviada pelas Entidades Prestadoras de Cuidados de Saúde referente à faturação das despesas com cuidados de saúde dos segurados de outro Estado-Membro ou de país terceiro com o qual Portugal tenha Acordo Bilateral e que para o efeito tenham apresentado um documento de atestado de direito válido.</p>
<p>O ambiente de execução aplicacional é totalmente baseado e orientado às tecnologias Web, isto é, serão desenvolvidos utilizando a tecnologia Apache Wicket, assegurando que os utilizadores finais podem realizar todas as interações com o sistema através do seguinte browser web:</p>

<ul>
	<li>Google Chrome
	</li>
</ul>

<p>Todas as comunicações ao nível da camada de aplicação do Modelo OSI (Open System Interconnection) são realizadas tirando partido do protocolo HTTP/HTTPS.</p>
<p>O manual apresenta as funcionalidades separadas por tipo de perfil (ACSS e EPSNS) e orienta quanto às regras de validação da informação da faturação dessas despesas, para posterior importação para a área de Despesas Efetivas na vertente de Portugal Credor no SIGAI.</p>


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

<p id="novoUser"></p>
**Novo utilizador**
Para que um novo utilizador tenha acesso a aplicação, deve solicitar à equipa de suporte da SPMS, via [servicedesk@spms.min-saude.pt](servicedesk@spms.min-saude.pt), indicando o nome da aplicação do assunto do email [FAIT]. O email deve conter as seguintes informações:

**	Nome de Utilizador;
**	Email;
**	Instituição que pertence.

O utilizador receberá um email da equipa de suporte com os dados da nova credencial de acesso.

<p id="altPass"></p>
**Alterar Senha**
A aplicação permite que o utilizador altere a sua própria palavra passe, a qualquer momento. Ao carregar no botão das opções avançadas logo, situado no canto superior direito da página, surgirá a opção “Alteração de Senha”.

![figRecPass](img/capitulo4/4_1RecPass1.png)

<p class="caption" id="figRecPass">Alterar palavra-passe</p>

Após clicar em **Alterar palavra-passe** da Senha é apresentada a seguinte página de alteração da password:

![figRecPass](img/capitulo4/4_1RecPass2.png)

<p class="caption" id="figRecPass">Página para alterar a palavra-passe</p>


O utilizador deve preencher todos os campos e clicar no botão **Alterar**.

<p id="recPass"></p>
**Recuperar Senha**
Se por qualquer motivo, o utilizador precisar de uma nova senha deverá clicar em **Recuperar Senha** e preencher o campo do formulário, com o nome do utilizador, conforme a figura abaixo e clicar em **Enviar**. 

![figRecPass](img/capitulo4/4_1RecPass3.png)

<p class="caption" id="figRecPass">Recuperação de senha</p>

Após a submissão do pedido de recuperação de senha, o utilizador receberá, no email associado ao nome de utilizador submetido, as instruções para reposição da palavra-passe.

<p id="closesession"></p>
**Terminar Sessão**
O utilizador pode sair do sistema a qualquer momento. Para tal, deve clicar no botão Terminar Sessão, representado pelo ícone <img alt="logo" src="img/capitulo4/4_1SessionIcon.png"> , situado no campo superior direito da página. 

<p id="permissoes-e-perfis"></p>
## 4.2. Permissões e Perfis

O menu principal terá disponível um determinado conjunto de módulos de acordo com o perfil que este tem associado à sua conta. É possível, na tabela seguinte, consultar os tipos de perfis existentes na aplicação do FAIT, bem como, os módulos a que estes têm acesso.

<table>
	<thead>
	<tr>
		<th><h5> Perfil </h5></th>
		<th><h5> Módulo </h5></th>
		<th><h5> Permissões </h5></th>
	</tr>
	</thead>
	<tbody>
		<tr>
			<td rowspan="5">EPSNS</td>
			<td>
				<ul>
				<li>Registar a Fatura</li>
				</ul>
			</td>
			<td>
				<ul>
				<li> Inserir fatura através do preenchimento manual do formulário S080 (E125). </li>
				</ul>
			</td>
			
		</tr>	
	</tbody>		
</table>

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
