## Display
`display: inline;`  - Deixa itens que estavam separados padronizados para uma linha
antes:
![[Pasted image 20231227145846.png]]
depois:
![[Pasted image 20231227145904.png]]

`display: block;`  - Deixa os elementos da mesma forma que um paragrafo 
antes:
![[Pasted image 20231227150108.png]]
depois:
![[Pasted image 20231227150122.png]]


## Float
`Float: left;`  - Serve para definir o posicionamento de um item
antes:
![[Pasted image 20231227163056.png]]
depois:
![[Pasted image 20231227163109.png]]

`overflow: auto; ` - Dita que o espaçamento de um item vai ser levado em consideração
depois:
![[Pasted image 20231227163132.png]]

## Position
`position: relative;`  - Torna um elemento relativo a algo 
![[Pasted image 20231228100030.png]]
`position: absolute;` - torna um elemento relativo ao documento, não a outro elemento, deixando ele por cima de todos os outros

`position: fixed;` - Define que um elemento fique fixo na tela não importa as alterações feitas

`position: sticky;` 
`top: 0px;`
- Define que um elemento ira ser alterado pela pagina até que chegue em uma certa posição (No exemplo acima até que chegue ao topo da página)


`z-index: 0, 1, -1`  - Define que um elemento fique a frente ou não de outro elemento (valores positivos a frente, negativos atras)

## FlexBox
#### `display: flex;`  - Se for definido somente o display flex os itens irão ficar preenchendo completamente o espaço do container definido em grade
antes:
![[Pasted image 20231228104405.png]]
depois:
![[Pasted image 20231228104348.png]]



#### `flex-direction: (#) ` - Define a direção e formato que os elementos irão ficar
`row`  - Modo padrão do flex-box mostrado acima no "depois"
`row-reverse`  - Inverte a ordem dos itens

`colum` - Direção normal do html, em colunas mostrado acima no "antes"
`colum-reverse`  - Direção é invertida na vertical



#### `flex-wrap: (#)`  - Define oque acontece com os itens quando falta espaço para eles no container

`wrap`  - Define que os elementos podem se adaptar indo para outras linhas se necessário 
![[Pasted image 20231228111224.png]]

`no-wrap`  - Define que os elementos não podem ir para outras linhas

`wrap-reverse` - Altera a ordem que os elementos se adaptam
![[Pasted image 20231228111254.png]]



#### `justify-content: (#)`  - Define como os elementos vão se justificar horizontalmente

`center`  - Centraliza os elementos horizontalmente
![[Pasted image 20231228111401.png]]

`flex-start`  - Centraliza os elementos a esquerda
![[Pasted image 20231228111511.png]]

`flex-end ` - Centraliza os elementos a direita
![[Pasted image 20231228111528.png]]

`space-arround`  - Distribui os itens com espaços iguais em volta
![[Pasted image 20231228111550.png]]

`space-betwen` - Distribui os itens de forma que o primeiro e o ultimo fiquem grudados na borda
![[Pasted image 20231228111610.png]]



#### `align-items: (#)`  - Define como os elementos vão se justificar verticalmente

`flex-start`  - Ajusta os itens baseado no tamanho do conteúdo dentro deles
![[Pasted image 20231228111820.png]]

`flex-end`  - Ajusta os itens baseado no tamanho do conteúdo mas de baixo para cima
![[Pasted image 20231228111909.png]]

`center`  - Centraliza os itens verticalmente
![[Pasted image 20231228112132.png]]



 `Gap: (#px)`  - Define o espaçamento entre os itens no interior do container
 ![[Pasted image 20231228114553.png]]


`row-gap: (#px)`  - Define o espaçamento entre as linhas do layout
![[Pasted image 20231228114736.png]]


`colum-gap: (#px)` - Define um espaçamento entre as colunas
![[Pasted image 20231228114851.png]]



### Elementos dentro dos Flex Itens (child)

![[Pasted image 20231228115930.png]]

`Order` - Altera a ordem dos itens, sendo 0 sem ordem nenhuma, e quanto maior o valor mais em ultimo o item vai ficar
![[Pasted image 20231228120059.png]]
![[Pasted image 20231228120132.png]]


`flex-grow: 1;`  - Define a responsabilidade dos itens que tiverem essa propriedade de preencher completamente o container (quanto maior o número maior a responsabilidade de preencher)
![[Pasted image 20231228120334.png]]



#### `align-self: (#)`  - Define como um elemento deve ser alinhado indecentemente dos outros

`flex-end`  - Dita que o elemento deve ficar abaixo
![[Pasted image 20231228121236.png]]

