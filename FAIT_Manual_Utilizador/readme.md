# Manual Utilizador FAIT

[Manual utilizador FAIT](https://spms-ai.github.io/FAIT_REPO/FAIT_Manual_Utilizador) para ver o resultado do repositório.

## Directorias

* **content** - conteúdo em markdown
* **css** - ficheiros de estilo
 - *main.css* estilo principal
 - *style.css* estilo personalizado
* **highslide** - imagens essenciais para zoom ([highslide webpage](http://highslide.com/))
* **img** - imagens incluidas no manual 
 - *pages* - imagens das páginas web da aplicação
* **js** - bibliotecas e ficheiros de JavaScript
* **index.html** - página inicial
* **indice.html** - página de indice

## Melhorias

* Compatibilidade com todos os browsers (Chrome, Opera, Safari, Firefox 3.6+, IE6+) e Mobile
* Normalizações de css
* Instalações

## A ter em atenção
No directório superior encontra-se a pasta *_layouts* essencial para definição do output dos ficheiros de markdown.

## Ajuda
### Como proceder quando se pretende colocar no manual de utilizador uma imagem que tem menos de 80% do tamanho da página?
 * Na pasta ''cs'', no ficheiro ''style'', adicionar a imagem em causa em ''paginas'';
 * Na pasta ''js'' no ficheiro ''script'', adicionar a imagem na função "function zommClickImagem()".
  
 
### Como proceder quando se pretende adicionar um novo módulo?
* No ficheiro ''index'', adicionar o módulo em ''div id="paginas"'';
* No ficheiro ''index'', adicionar o módulo em ''script'';
* No ficheiro ''Indice'', adicionar o módulo à lista.

### Como proceder quando se pretende remover um  módulo?
* No ficheiro ''index'', remover o módulo em ''div id="paginas"'';
* No ficheiro ''index'', remover o módulo em ''script'';
* No ficheiro ''Indice'', remover o módulo à lista.
* remover o ficheiro de content


### Como proceder para adicionar hiperligações?
* Ir à aplicação ver qual é o #hashtag;
* Ir ao índice e acrescentar href #hashtag;
* Ir ao ficheiro markdown e pôr <p id= hashtag> </p> (antes do header h1/h2).


