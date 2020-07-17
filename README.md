# CSS Grid e Flexbox

<i>Exemplos simples de como utilizar o CSS Grid junto com Flexbox.

<b>Usar flexbox para elementos no eixo de x e CSS Grid no eixo de x e y</b>

* Exemplo 1 - Utilização do flexbox 
          <propriedades> <br>
            * <b>display:</b> flex - <i> Define a propriedade flex <br>
            * <b>flex-wrap:</b>  wrap - <i> Quando o elemento deve quebrar <br>
            * <b>flex:</b>  1 1 200px <i> 1 - quando o elemento expande  / 1-shrink - o quanto estica / 200px = o tamanho do elemento <br>
            
* Exemplo 2 - Utilização Grid Layout  <br>
          <propriedades>
            * <b>grid-tamplate-columns:</b> Define quantidade de colunas no container   <br>
            * <b>grid-gap:</b> Seleciona o intervalo (espaço) <br> 
            * <b> grid-columm:</b> Seleciona colunas  <br>
            * <b>grid-row:</b> Seleciona as linhas <br>
            * <b>order:</b> Modifica a ordem do elemento   <br>
            
*Exemplo 3 - CSS Grid 3
           <propriedades><br>
            <b>Foi utilizado o flexbox para alinhar a legenda a imagem. Dentro do container da imagem foram definidas duas linhas, sendo uma para segurar a imagem e a outra
            para segurar o parágrafo. Após isso, foi definido para a imagem o grid-row indo da linha 1 a linha 3 e o parágrafo na linha 2, ficando assim por cima da imagem</b>
            
            .grid3-item img{
                grid-column: 1;
                grid-row: 1/3;
                align-self: end;
            }

            .grid3-item p{
                background: rgba(0,0,0,0.6);
                padding: 10px;
                color: white;
                grid-column: 1;
                grid-row: 2;
                align-self: end;
            }
