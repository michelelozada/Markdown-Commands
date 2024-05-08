> **Quebrando linhas e espaçando o texto**      
> Repositório: Comandos Markdown  
> GitHub: @michelelozada
&nbsp; 

&nbsp; 
## 1. Quebra de linhas 
Em markdown, ao menos aqui no GitHub, separar duas linhas com *enter* não fará com que elas 'quebrem'.   
Para isso, ao fim da primera linha, basta deixar dois espaços em branco (através da barra de espaços).  

#### :black_medium_small_square: A renderização quando se utilizou apenas o enter: 
Primeira linha
Segunda linha

#### :black_medium_small_square: A renderização quando foram deixados dois espaços após a primeira linha:
Primeira linha      
Segunda linha  

#### :black_medium_small_square: A renderização quando foi literalmente deixada uma linha entre as linhas:
Primeira linha     

Segunda linha  

&nbsp;     

## 2. Deixando mais de uma linha em branco
Para isso, utilize a barra invertida para cada linha em branco que desejar incluir.  
#### :black_medium_small_square: A marcação 
```markdown
Primeira linha 
\
\
\
Quinta linha 
```
#### :black_medium_small_square: A renderização 
Primeira linha 
\
\
\
Quinta linha  

&nbsp;   

## 3. Espaçamento entre blocos de textos
Para adicionar espaço entre dois blocos de textos, você pode utilizar o código `&nbsp;` da forma abaixo.
#### :black_medium_small_square: A marcação 
```markdown
Este é o primeiro bloco de texto.

&nbsp;

Já este é o segundo bloco de texto.
```
#### :black_medium_small_square: A renderização 
Este é o primeiro bloco de texto.

&nbsp;

Já este é o segundo bloco de texto.

&nbsp;

## 4. Inserindo espaços em branco 
#### :black_medium_small_square: A marcação 
```markdown
A primeira linha.      
&nbsp;A segunda linha começando um pouco recuada à direita.  
&nbsp;&nbsp;Continuação da linha.
```
#### :black_medium_small_square: A renderização 
A primeira linha.      
&nbsp;A segunda linha começando um pouco recuada à direita.  
&nbsp;&nbsp;Continuação da linha.

&nbsp;

<div align="center">
<a href="https://github.com/michelelozada/Comandos-Markdown">[Voltar à tela inicial do repositório]</a>
</div>