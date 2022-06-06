> **Exibindo trechos ou blocos de código via linguagem Markdown**      
> Repositório: Comandos Markdown  
> GitHub: @michelelozada
&nbsp;
     
&nbsp; 
&nbsp;    
**1. Para exibição de comandos ou trechos de código**  
---
###### >> Marcação 
```
Em Python, há uma série de funções nativas que convertem valores de um tipo em outro.   
A função `int` recebe um valor e o converte para inteiro. 
A função `float` converte inteiros e strings em números em ponto flutuante.  
E a função `str` converte os valores para o tipo string.
```
###### >> Renderização 
Em Python, há uma série de funções nativas que convertem valores de um tipo em outro.  
A função `int` recebe um valor e o converte para inteiro.  
A função `float` converte inteiros e strings em números em ponto flutuante.  
E a função `str` converte os valores para o tipo string. 
&nbsp;
     
&nbsp;     
**2. Para exibição de um bloco de código** 
---
###### >> Marcação    
<pre>
```
A marcação assim utilizada
faz com que o bloco de código
multilinhas
seja assim exibido
```  
</pre>
###### >> Renderização   
````
A marcação assim utilizada
faz com que o bloco de código
multilinhas
seja assim exibido
````
&nbsp;
     
&nbsp;  
**3. Destacando blocos de código de acordo com a linguagem utilizada** 
---
Logo após a primeira marcação de bloco de código, inclua o [código da linguagem determinado para esta função](https://rdmd.readme.io/docs/code-blocks 'Clique aqui para consultar a lista completa'): 
###### >> Marcação para código JavaScript   
<pre>
```js
let d1 = true;
let d2 = false;
console.log(typeof d1)
console.log(typeof d2)
```  
</pre>
###### >> Renderização   
````js
let d1 = true;
let d2 = false;
console.log(typeof d1)
console.log(typeof d2)
````
###### >> Marcação para código Python 
<pre>
```py
n1 = 1
n2 = 1
print("TABUADA DE MULTIPLICAÇÃO")
for n1 in range (1,11,1):
    print('\nTabuada do', n1)
    for n2 in range (1,11,1):
        print(n1 ,'x', n2 ,'=', n1*n2)
```  
</pre>
###### >> Renderização   
````py
n1 = 1
n2 = 1
print("TABUADA DE MULTIPLICAÇÃO")
for n1 in range (1,11,1):
    print('\nTabuada do', n1)
    for n2 in range (1,11,1):
        print(n1 ,'x', n2 ,'=', n1*n2)
````