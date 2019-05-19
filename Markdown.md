## MARKDOWN

### O que é Markdown?

**Markdown** é um tipo de _markup language_, que por usa vez é uma linguagem utilizada para aplicar elementos de  formatação em palavras ou parte de um texto simples.

Note que escrever um texto com Markdown é diferente de escrever um texto com editor  [WYSIWYG][link1] como o Word da Microsoft, no qual, em termos gerais, podemos dizer que se adiciona a formatação do texto apenas selecionando a palavra ou conjunto de palavras e clicando em um botão e as mudanças na formatação do texto são imediatamente visualizadas. Com Markdown, assim como em qualquer outra _markup language_, você formata o texto adicionando a sintaxe da linguagem referente ao tipo de formatação desejado. Dependendo da ferramenta utilizada para escrever o seu texto em Markdown você será capaz de pré-visualizar o resultado ou não. Porém, indpendentemente de ver ou não o texto formatado, a sintase do Markdown foi pensada de forma a não interferir na leitura mesmo que o texto ainda não tenha sido compilado.  

___

### Aplicações

Apesar de não ter o poder de formatação de alguns editores [WYSIWYG][link1], Markdown pode ser utilizado para escrever quase todo tipo de texto, tal como um  ou livro, uma lista de compras ou chek-list de atividades. Porém, uma das principais aplicações do Markdown é produzir textos formatados para sites de internet, tendo sido esta uma das motivações de sua criação existem uma infinidade de aplicações do Markdown na internet.  

___

### O pouco que já aprendi.

Apesar de ser bastante fácil e intuitivo de se aprender a seguir estarei listando e explicando o funcionamento de algumns comandos que já aprendi, tanto para consultas futuras como para ajudar a tirar dúvidas de algum iniciante como eu.

#### Negrito e Itálico

Começando pelos estilos de formtação mais usuais e simples, podemos fazer com que uma palavra seja destacada em negrito no texto apenas adicionando dois asteríscos antes e depois da palavra \(ex.: \*\*negrito\*\* produz esse resultado **negrito**\). Uma outra forma de deixar uma palavra em negrito é adicionando dois underlines antes e depois da palavra \(ex.: \_\_negrito\_\_ produz esse resultado __negrito__\). Além disso, para fazer com que um conjunto de palavras fique destacada em negrito não é necessário colocar essa sintaxe para cada termo da frase, basta usar a sintaxe antes da primeira palabra e ao final da última \(ex.: **Esta é uma frase em negrito**\).  

O itálico não poderia ser muito diferente. Para destacar a palavra em itálico, basta colocar antes um underline antes e um depois da palavra ou de um conjunto de palavras \(ex.:\_itálico\_ produz esse resultado _itálico_; ou ainda _Essa é uma frase em itálico_ para um conjunto de palavras\). Outro modo de aplicar a fortamação itálico é utilizando apenas um asteríscos antes e depois do termo \(ex.:\*itálico\* produz esse resultado *itálico*\).  

Ainda é possível mesclar itálico e negrito, basta adicionar as duas sintaxe à palavra considerando que a última sintaxe aberta deve ser a primeira a ser encerrada \(ex.:\*\*\_ BODOCK\_\*\* produz esse resultado **_BODOCK_**\).  

___

#### Títulos e Cabeçalhos

Títulos e cabeçalhos são importantes na confecção de um texto pois ajudam a destacar a divisão das seções desse texto. Pensando nisso o Markdown também possui 6 marcações diferentes para cabeçalhos, sendo a 1 a maior e a 6 a menor. Para indicar em um texto formatado com Markdown que determinada linha é um cabeçalho basta adicionar \# em quantidade necessária para definir o tamanho do cabeçalho que você quer criar. Por exemplo:  

\# Cabeçalho nº 1  
\#\# Cabeçalho nº 2  
\#\#\# Cabeçalho nº 3  
\#\#\#\# Cabeçalho nº 4  
\#\#\#\#\# Cabeçalho nº 5  
\#\#\#\#\#\# Cabeçalho nº 6  

A sintaxe acima resulta na seguinte formatação:

# Cabeçalho nº1
## Cabeçalho nº2
### Cabeçalho nº3
#### Cabeçalho nº4
##### Cabeçalho nº5
###### Cabeçalho nº6

Cabeçalhos podem ainda ser destacado com negrito e itálico.

\#\#\# \*\*Cabeçalho\*\* \*nº 3\* resulta em:

### **Cabeçalho** *nº 3*

Além disso, é importante dar um espaço entre o último marcador \# e o primeiro caracter do cabeçalho. Caso contrário o resultado acima seria

###**Cabeçalho** *nº 3*

Há também a possibilidade de tornar as palavras cabeçalho um hiperlink, sobre a sintaxe de links falarei mais a frente.

### [O começo de tudo](https://github.com/pbbodock/o-comeco-de-tudo)

Por fim, apesar de não ter esgotado tudo o que é possível fazer com Markdown em cabeçalhos dou-me por satisfeito e irei acrescentando as possibilidades de formatação nesse texto a medida que forem surgindo a necessidade.

___

#### Parágrafos

Não há nenhuma necessidade de sintaxe no inicio de cada parágrafo para que o Markdown entenda como um parágrafo. Se você gosta de espaçamento entre os parágrafos, basta deixar uma linha em branco entre cada parágrafo. Como no exemplo a seguir

Código:

  Este é um parágrafo.  
  "linha em branco"  
  Este é um segundo parágrafo  

Resulta em:

Este é um parágrafo.

Este é um segundo parágrafo.

Uma outra forma é simplesmente aplicando dois espaços em branco no final da frase para dar uma quebra de linha e ir para a linha seguinte.

  Este é um parágrafo.--  
  Este é um segundo parágrafo.

Lembrando que o -- deve ser substituído por dois espaços em branco. O resultado será:

Este é um parágrafo.  
Este é um segundo parágrafo.

___

#### Blockquotes

Blockquotes definem uma seção do texto que está sendo citada de outra fonte. Para cirar um blockquote em Markdown basta usar \> no inicio do parágrafo.

\> Este é um blockquote.  

> Este é um blockquote.

Também é possível cirar um blockquote com múltiplos parágrafos, apenas adicionando \> no inicio de cada parágrafo.

\>Este é o primeiro parágrafo do blockquote.  
\>Este é o segundo parágrafo do blockquote.  

Deverá resultar em algo semelhante a isso:

> Este é o primeiro parágrafo do blockquote.  
> Este é o segundo parágrafo do blockquote.  
>
> Este é o terceiro parágrafo do blockquote.

___


#### Listas Ordenadas e não Ordenadas

##### Listas ordenadas:

Criar uma lista ordenada é simples. Basta adiconar linhas com números seguidos de um ponto e do período. Os números não precisam estar em ordem, mas a lista deve ser iniciada com o número 1.

\1. Primeiro item;  
\3. Segundo item;  
\2. Terceiro item;  

1. Primeiro item;
3. Segundo item;
3. Terceiro item;

##### Listas não ordenadas:

Para criar uma lista não ordenada basta adicionar \* asterísco, - sinal de subtração, ou + sinal de adição.


\- Primeiro item.  
\- Segundo item.

- Primeiro item.
- Segundo item.

\* Primeiro item.  
\* Segundo item.

* Primeiro item.
* Segundo item.

\+ Primeiro item.  
\+ Segundo item.

+ Primeiro item.
+ Segundo item.

Para criar uma lista aninhada, basta identar a linnha com tab.

\+ Primeiro item.  
'tab' \+ Segundo item.

+ Primeiro item.  
  + Segundo item.

Para adicionar algum elemento em uma lista sem perder a ordem, basta identar a linha e inserir o elemento, em alguns casos se faz necessário deixar uma linha em branco entre o elemento e a sequência da lista.

\1. Primeiro item.  
\2. Segundo item.  

'tab' Este é um paragrafo.  

\3. Terceiro item.  


1. Primeiro item.
2. Segundo item.

    Este é um paragrafo.

3. Terceiro item.

\1. Primeiro item.  
\2. Segundo item.  
'tab' Este é um blockquote.  
"linnha em branco"  
\3. Terceiro item.


1. Primeiro item.
2. Segundo item.
  > Este é um blockquote.

3. Terceiro item.

___

#### Links e Imagens

Para tornar uma palavra um hiperlink em Markdown basta colocar a palavra entre colchetes seguida do link entre parenteses \(ex.: \[Google\]\(www.google.com\) cria um hiperlink para o site de busca na palavra [Google](www.google.com)\).

Quando o hiperlink vai se repetir várias vezes ao longo do texto é possível criar uma palavra de referência para esse hiperlink de forma que se for preciso mudar o endereço de destino isso seja feito em apenas um local do texto e todos os outros serão atualizados. Para isso, basta colocar a palavra que será o hiperlink entre colchetes seguido da palavra de referência também entre colchetes e em algum ponto do texto definir o endereço da referência com a palvra de referência entre colchete seguido de dois pontos e o endereço entre parenteses. Exemplo:

\[Google\]\[referênca\]  
\[site de busca\]\[referência\]  

\[referência\]: (www.google.com)  

[Google][referência]  
[site de busca][referência]

[referência]:(www.google.com)

A sintaxe utilizada para inserir uma imagem em Markdown é bastante similar a utilizada para inserção de link, para imagem basta utilizar um ponto de exclamação antes do primeiro colchete \(ex. \!\[imagem\]\(endereço da imagem\)\)

\!\[Luffy\]\(https://www.closeup-shop.com/media/oart_0/oart_o/oart_64154/thumbs/824130_2079048.jpg?PHPSESSID=fnvl0lclj39pvqla1hun82err5\)

![Luffy](https://www.closeup-shop.com/media/oart_0/oart_o/oart_64154/thumbs/824130_2079048.jpg?PHPSESSID=fnvl0lclj39pvqla1hun82err5)

#### Caracteres especiais

Markdown utiliza alguns caracteres especiais para codificar sua sintaxe, tal como \*, \#, \[\], \(\),\_, dentre outros. Caso seja necessário utilizá-los na descrição do texto é necessário utilizar uma sintaxe que anula a interpretação desses caracteres como um comando de formatação. Para tanto, basta utilizar a barra invertida \ antes do caracter especial.

### FINALMENTES

Por fim, longe de cobrir todas as possibilidades de formatação que o Markdown propicia na criação de textos acredito que o contéudo aqui apresentado cobrirá minhas principais necessidades, pelo menos incialmente, de formatação para criação dos meus relatórios de progresso nessa jornada de arpendizado. A medida que novos elementos forem sendo necessário esse texto também será atualizado.


[link1]:(https://en.wikipedia.org/wiki/WYSIWYG)
