> **Quebra de linhas e inclusão de espaços em branco**      
> Repositório: Comandos Markdown  
> GitHub: @michelelozada
&nbsp; 

&nbsp;    
**1. Quebra de linha**  
---
Em markdown, ao menos aqui no GitHub, separar duas linhas com *enter* não fará com que elas 'quebrem'.   
Para isso, ao fim da primera linha, basta deixar dois espaços em branco (através da barra de espaços).  

###### >> Utilizando apenas o enter: 
Primeira linha
Segunda linha

###### >> Utilizando dois espaços após a primeira linha:
Primeira linha      
Segunda linha  
&nbsp; 

&nbsp;     
**2. Deixando uma ou mais linhas em branco**  
---
Utilize a barra invertida, sendo que a primeira delas deve estar no fim da linha que antecede esta quebra.  
Depois, use uma barra invertida para cada linha em branco que desejar incluir.  
###### >> Marcação 
```markdown
Primeira linha \
\
\
\
Quarta linha 
```
###### >> Renderização 
Primeira linha \
\
\
\
Quarta linha  
&nbsp;   
**Observação:** quando HTML também é suportando, é possível utilizar a tag <br\> para produzir a quebra de linha.
###### >> Marcação 
```markdown
Primeira linha<br/>
<br/>
<br/>
Quarta linha  
```
&nbsp; 

&nbsp;   
**3. Espaçamento entre parágrafos**  
---
Para adicionar espaço entre dois parágrafos, utilize o código `&nbsp;` da forma abaixo, deixando mais
dois espaços extras/em branco ao fim.
###### >> Marcação 
```markdown
Este é o primeiro parágrafo.
&nbsp; 

&nbsp;  
Já este é o segundo parágrafo. 
```
###### >> Renderização 
Este é o primeiro parágrafo.
&nbsp; 

&nbsp;  
Já este é o segundo parágrafo. 
&nbsp; 

&nbsp;   
**4. Inserindo espaços em branco**  
---
###### >> Marcação 
```markdown
A primeira linha.      
&nbsp;A segunda linha começando um pouco recuada à direita.
&nbsp;&nbsp;Continuação da linha.
```
###### >> Renderização 
A primeira linha.      
&nbsp;A segunda linha começando um pouco recuada à direita.
&nbsp;&nbsp;Continuação da linha.

&nbsp;

<div align="center">
<a href="https://github.com/michelelozada/Comandos-Markdown">[Voltar à tela inicial do repositório]</a>
</div>