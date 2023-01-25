> **Elaborando diagramas com a sintaxe Mermaid**  
> Repositório: Comandos Markdown  
> GitHub: @michelelozada
&nbsp;
     
&nbsp;  
A sintaxe Mermaid permite a criação de vários tipos de diagramas para projetos que, baseados em linguagem Markdown, são renderizados no navegador.    
&nbsp;     
Os vários modelos disponíveis de fluxogramas, diagramas UML, pie charts, etc. estão disponíveis [na sua página oficial](https://mermaid-js.github.io/mermaid/#/).
&nbsp;
     
&nbsp;      
:arrow_forward: **Exemplo 1 -** Criação de um diagrama de sequência baseado [neste exemplo aqui](https://www.qconcursos.com/questoes-de-concursos/questoes/0c70b814-09):    
#### :black_medium_small_square: Marcação para a criação do diagrama:
````
```mermaid
sequenceDiagram
    Secretária->>Interface: Solicitar matrícula
    Interface->>Aluno: obterAtributos()
    Aluno-->>Interface: retornar(atributos)
    Interface->>Secretária: Apresentar atributos
    Secretária->>Interface: Informar dados
    Interface->>Matricula: criarMatricula(dados)
    Matricula-->>Interface: apresentarMsgDadosInvalidos()
    Interface->>Secretária: Informar dados inválidos
    Secretária->>Interface: Cancelar matrícula
    Interface--xMatricula: Cancelar
```
````
&nbsp; 
#### :black_medium_small_square: A renderização do código acima:
```mermaid
sequenceDiagram
    Secretária->>Interface: Solicitar matrícula
    Interface->>Aluno: obterAtributos()
    Aluno-->>Interface: retornar(atributos)
    Interface->>Secretária: Apresentar atributos
    Secretária->>Interface: Informar dados
    Interface->>Matricula: criarMatricula(dados)
    Matricula-->>Interface: apresentarMsgDadosInvalidos()
    Interface->>Secretária: Informar dados inválidos
    Secretária->>Interface: Cancelar matrícula
    Interface--xMatricula: Cancelar
```
&nbsp;
     
&nbsp;      
:arrow_forward: **Exemplo 2 -** Criação de um fluxograma:    
#### :black_medium_small_square: Marcação para a criação do diagrama:
````
```mermaid
flowchart LR
    A(Início) --> B{media >= 7.0}
    B -->|Verdadeiro| C(O aluno está aprovado)
    B -->|Falso| D(O aluno ficou para prova final)
    C -->E(Fim)
    D -->E(Fim)
```
````
#### :black_medium_small_square: A renderização do código acima:
```mermaid
flowchart LR
    A(Início) --> B{media >= 7.0}
    B -->|Verdadeiro| C(O aluno está aprovado)
    B -->|Falso| D(O aluno ficou para prova final)
    C -->E(Fim)
    D -->E(Fim)
```
&nbsp;
     
&nbsp;      
:arrow_forward: **Exemplo 3 -** Criação de um pie chart:    
#### :black_medium_small_square: Marcação para a criação do diagrama:
````
```mermaid
pie showData
    title Intenção de voto por candidato
    "Candidato A" : 35.0
    "Candidato B" : 40.0
    "Candidato C" : 25.0
```
````
#### :black_medium_small_square: A renderização do código acima:
```mermaid
pie showData
    title Intenção de voto por candidato
    "Candidato A" : 35.0
    "Candidato B" : 40.0
    "Candidato C" : 25.0
```

&nbsp;

<div align="center">
<a href="https://github.com/michelelozada/Comandos-Markdown">[Voltar à tela inicial do repositório]</a>
</div>