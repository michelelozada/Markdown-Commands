> **Exibindo trechos ou blocos de código via linguagem Markdown**      
> Repositório: Comandos Markdown  
> GitHub: @michelelozada
&nbsp;
     
&nbsp; 
&nbsp;    
**1. Para exibição de um trecho de código**  
###### >> marcação 
``Caso deseje imprimir um trecho de código, `você deve envolver o código utilizando esta marcação aqui!`.``    

###### >> output 
Caso deseje imprimir um trecho de código, `você deve envolver o código utilizando esta marcação aqui!`.  
&nbsp;
     
&nbsp;     
**2. Para exibição de um bloco de código** 
###### >> marcação    
<pre>
```
A marcação assim utilizada
faz com que o bloco de código
multilinhas
seja assim exibido
```  
</pre>
###### >> output   
````
A marcação assim utilizada
faz com que o bloco de código
multilinhas
seja assim exibido
````
&nbsp;
     
&nbsp;  
**3. Destacando blocos de código de acordo com a linguagem utilizada** 
Logo após a primeira marcação de bloco de código, inclua o [código da linguagem determinado para esta função](https://rdmd.readme.io/docs/code-blocks 'Clique aqui para consultar a lista completa'): 
###### >> marcação para código JavaScript   
<pre>
```js
let d1 = true;
let d2 = false;
console.log(typeof d1)
console.log(typeof d2)
```  
</pre>
###### >> output   
````js
let d1 = true;
let d2 = false;
console.log(typeof d1)
console.log(typeof d2)
````
###### >> marcação para código Python 
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
###### >> output   
````py
n1 = 1
n2 = 1
print("TABUADA DE MULTIPLICAÇÃO")
for n1 in range (1,11,1):
    print('\nTabuada do', n1)
    for n2 in range (1,11,1):
        print(n1 ,'x', n2 ,'=', n1*n2)
````