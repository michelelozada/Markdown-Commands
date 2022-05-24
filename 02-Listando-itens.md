> **Listando itens via linguagem Markdown**      
> Repositório: Comandos Markdown  
> GitHub: @michelelozada
&nbsp;
     
&nbsp;     
**1. Lista numerada (aka listas ordenadas)**  
---
###### >> marcação   
```markdown
Lista:
   1. Primeiro item 
   1. Segundo item 
   1. Terceiro item 
```

###### >> output
Lista:
   1. Primeiro item 
   2. Segundo item 
   3. Terceiro item    
&nbsp;
     
&nbsp;    
**2. Lista de marcadores (aka listas não ordenadas)**  
---
###### >> marcação  
```markdown
Lista:
   * Primeiro item 
   * Segundo item
   * Terceito item
```
ou

```markdown
Lista:
   - Primeiro item 
   - Segundo item
   - Terceiro item
```
  
###### >> output 
Lista:
   * Primeiro item 
   * Segundo item
   * Terceiro item
&nbsp;
     
&nbsp;     
**3. Listas aninhadas**  
---
*Obs: Apenas para listas de marcadores*  

###### >> marcação   
```markdown
Lista:
- Primeiro item 
	- Primeiro subitem
	- Segundo subtitem
- Segundo item 
	- Primeiro subitem
		- Primeiro subsubtitem
		- Segundo subsubtitem
- Terceiro item 
```
  
###### >> output
Lista:
- Primeiro item 
	- Primeiro subitem
	- Segundo subtitem
- Segundo item 
	- Primeiro subitem
		- Primeiro subsubtitem
		- Segundo subsubtitem
- Terceiro item 
&nbsp;
     
&nbsp;     
**4. Lista de tarefas**  
---
###### >> marcação  
```markdown
Tarefas a realizar
- [x] Revisar o código
- [ ] Criar o repositório no GH
- [ ] Enviar arquivos para o GH
```
###### >> output
Tarefas a realizar
- [x] Revisar o código
- [ ] Criar o repositório no GH
- [ ] Enviar arquivos para o GH