# Hollywood Degrees

## Introdução

De acordo com o jogo "Six Degrees of Kevin Bacon", qualquer pessoa na indústria cinematográfica de Hollywood pode ser conectada a Kevin Bacon em seis etapas, onde cada etapa consiste em encontrar um filme em que dois atores estrelaram.

Nesse problema, estamos interessados ​​em encontrar o caminho mais curto entre dois atores escolhendo uma sequência de filmes que os conecte. Por exemplo, o caminho mais curto entre Jennifer Lawrence e Tom Hanks é 2: Jennifer Lawrence está conectada a Kevin Bacon por estrelar "X-Men: First Class” e Kevin Bacon está conectada a Tom Hanks por estrelar em “Apollo 13”.

## O que temos aqui

large e small são diretórios com os dados dos filmes e atores.
util.py define classes importantes para degrees.
degrees.py usa os dados de large/small, os nomes dos atores e retorna a distância entre eles.
smallDiagram representação gráfica dos dados em small.

## Como usar

### python degrees.py small
ou
### python degrees.py large

Depende de qual diretório você quer usar!

Para mudar a busca entre largura e profundidade basta mudar a classe de frontier(QueueFrontier para largura; StackFrontier para profundidade)

OBS: diretório large possui people.csv e people2.csv. Precisa copiar o conteudo de people2 para people 

## Projeto original

Projeto 0 do Curso: [CS50’s Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/2020/weeks/0/)