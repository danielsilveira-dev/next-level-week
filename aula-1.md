# aula-1
 - Cliente - Servidor
 - Cliente pede alguma coisa
 - Servidor prover coisas
 - HTTP (Hyper Text Transfer Protocol)
 - URL (Universal Resource Location)
 - Uma troca de dados

## Front-end
 - HTML
 - CSS
 - JavaScript

## Back-end
 - JavaScript

## HTML
 - Hypertext(Hiper texto)
 - Markup(Marcação de texto)
 - Language(Linguagem)

## TAGS HTML [ELEMENTOS]

 - span - <span></span> `/* Tag inline */`

 - Imagem - <img src="" alt="" /> `/*src="" para o local da imagem e alt="" para acessibilidade, leitores de tela ler o que está no local da imagem*/`

 - Título <h1></h1>
          <h3></h3>

 - Link - <a href=""></a>

 - Botão - <button></button>

 - Estilização - <style type="text/css"></style> Para estilização na própria página HTML

 - Meta - <meta charset="utf-8">

 - Link - <link rel="stylesheet" href="caminhoDoArquivo"> Link externo da estilização da página

 - DIV - <div></div>

## DOM
 Pressionando F12 na tela do navegador, você poderá ver o HTML do site que você está visitando.
 - Document
 - Object
 - Model

## Site de Fontes
 - [Google Fonts](https://fonts.google.com/)

## CSS
 No CSS você pode selecionar[seletor] os elementos colocando o nome da TAG que você quer estilizar.
 Ex:  
 ```
 html{
 	propriedade: valor;
 }
 ```  
 - Comentários no CSS `/**/`
 - O `class=""` você pode colocar na tag inicial dos elementos para editar as propriedades dele ou classificar o mesmo.
 - O "." é uma referência para uma classe no arquivo CSS
 - O "#" é uma referência para uma identificação ou seja, um id  
 ```
  elemento {
  	background-color: cor; /* Coloca uma cor de fundo */
  	max-width: 1100px; /* Largura máxima */
  	margin-left:auto; /* Define uma largura padrão automática */
  	margin-right: auto; /* Define uma largura padrão automática */
  	background-url: url('./image/image.svg'); /* Adiciona um arquivo de imagem no elemento */
  	background: url('./image/imagem.svg') no repeat; /* Inserção de imagens simplicado(Shorthand) */
  	background-position: 35vw bottom;
  	height: 100vh; /* viewport height pega a altura da tela do navegador */
  	background-image:url('caminhoDoArquivo');
  	font-weight: 300; /* Peso da fonte */
  	color: #322153;
  	text-decoration: none;
  	border-radius: 8px; /* Adiciona uma borda conforme a quantidade de pixels adicionada */
  	transition: 400ms; /* Adiciona um tempo de transição da cor conforme interação */  	
 }
 ```  
 - .page-home e apertar o tab cria uma div com class page-home
 - #page-home cria uma div com id page-home
 - Pixel é uma unidade de medida fixa, portanto sempre será o que for definido
 - porcentagem "%" é uma maneira inteligente de dimensionar os elementos no site
 - vh: viewport height pega a altura da tela do navegador
 - `max-width: 1100px;`
 - `margn-left: auto;`
 - `margn-right: auto;`
 - `margn: 0 auto; /* Dois valores na propriedade margin: 0 (Para cima e para baixo) auto(margem padrão para esquerda e para direita) */`

## MODELO DE CAIXAS [BOX MODEL]
 - Toda caixa tem: Largura, altura, espaçamentos, preenchimentos, bordas, cor, fundo e a maneira que é vista pelo HTML(display)
 - Alinhamentos, posicionamentos
 - A página HTML possui um modelo de caixas.
 - Cada tag possui seu valor específico de CSS
 - Padrão de uma caixa
 - Caixas:Pai>Filho
 - TAGS inline não ocupam linha inteira
 - Tags de bloco ocupam linha inteira

## RELOAD DA PÁGINA
 - CTRL R no DOM

## HTML SEMÂNTICO
 - Cada elemento possui um significado para os motores do Google
 - HEADER - <header></header>
 - NAV - <nav></nav>
 - ASIDE - <aside></aside>
 - MAIN - <main></main>
 - FOOTER - <footer></footer>

## FLEX
 - Abaixo, o elemento com essa propriedade, irá ficar em colunas
 Ex:
 ```
 header {
 	display: flex; /* Coloca os items internos em colunas */
 	align-items: center; /* alinha os items internos em uma linha no eixo x */
 	justify-content: space-between; /* Justifica o conteúdo interno no eixo x e cria um espaço entre eles*/
 	height: 100%;
 	flex-direction: column;
 }
 ```  
 ```
 .content {
 	width: 90%;
  }
 ```