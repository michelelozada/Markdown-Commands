> **EExibindo trechos e blocos de código**      
> Repositório: Comandos Markdown  
> GitHub: @michelelozada
&nbsp;
     
&nbsp; 
   
## 1. Para exibição de comandos ou trechos de código

#### :black_medium_small_square: A marcação 
```
Em Python, há uma série de funções nativas que convertem valores de um tipo em outro:  
A função `int` recebe um valor e o converte para inteiro. 
A função `float` converte inteiros e strings em números em ponto flutuante.  
E a função `str` converte os valores para o tipo string.
```
#### :black_medium_small_square: A renderização 
Em Python, há uma série de funções nativas que convertem valores de um tipo em outro:  
A função `int` recebe um valor e o converte para inteiro.  
A função `float` converte inteiros e strings em números em ponto flutuante.  
E a função `str` converte os valores para o tipo string. 
     
&nbsp;     

## 2. Para exibição de um bloco de código

#### :black_medium_small_square: A marcação    
````
```
A marcação assim utilizada
faz com que o bloco de código
multilinhas
seja assim exibido
```  
````
#### :black_medium_small_square: A renderização   
````
A marcação assim utilizada
faz com que o bloco de código
multilinhas
seja assim exibido
````

&nbsp;
  
## 3. Utilizando a sintaxe de uma linguagem específica dentro do bloco de código
&nbsp;

Logo após a primeira a marcação de bloco de código, inclua o código da linguagem desejada [saiba mais sobre isso aqui](https://docs.readme.com/rdmd/docs/code-blocks#language-support 'Clique aqui para consultar a lista completa'): 
#### :black_medium_small_square: A marcação para código JavaScript   
````
```js
let d1 = true;
let d2 = false;
console.log(typeof d1)
console.log(typeof d2)
```  
````
#### :black_medium_small_square: A renderização   
````js
let d1 = true;
let d2 = false;
console.log(typeof d1)
console.log(typeof d2)
````
#### :black_medium_small_square: A marcação para código Python 
````
```py
n1 = 1
n2 = 1
print("TABUADA DE MULTIPLICAÇÃO")
for n1 in range (1,11,1):
    print('\nTabuada do', n1)
    for n2 in range (1,11,1):
        print(n1 ,'x', n2 ,'=', n1*n2)
```  
````
#### :black_medium_small_square: A renderização   
````py
n1 = 1
n2 = 1
print("TABUADA DE MULTIPLICAÇÃO")
for n1 in range (1,11,1):
    print('\nTabuada do', n1)
    for n2 in range (1,11,1):
        print(n1 ,'x', n2 ,'=', n1*n2)
````

&nbsp;

<div align="center">
<a href="https://github.com/michelelozada/Comandos-Markdown">[Voltar à tela inicial do repositório]</a>
</div>