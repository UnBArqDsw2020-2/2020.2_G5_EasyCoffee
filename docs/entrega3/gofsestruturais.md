# GoFs Estruturais

## Adapter

<p align="justify">O Adapter é um padrão de projeto clássico dos GoFs estruturais. Compõem padrões nos quais o objetivo é identificar como entender relacionamentos entre classes e objetos de uma forma simples. Esse padrão é tipicamente usado quando um módulo incompatível necessita ser integrado com um módulo já existente sem que haja nenhuma modificação no código fonte. 
Há duas variantes do Adapter: Object Adapter que depende da composição e a Class Adapter que depende da herança.</p>

### Uso no projeto e justificativa

## Bridge

### Uso no projeto e justificativa

## Composite

<p align="justify">Usando o padrão Composite é possível criar árvores hierárquicas de objetos de uma maneira uniforme sem grande complexidade. Compondo objetos em estruturas de árvores para representar relações hierárquicas parte-todo. O padrão Composite permite aos clientes tratar objetos de forma individual e composições de objetos uniformemente, ou seja, o cliente pode ser capaz de aplicar as mesmas operações sobre ambas agregações de objetos(todo) e objetos individuais(parte).
</p>

### Uso no projeto e justificativa

## Decorator

### Uso no projeto e justificativa

## Facade
<p align="justify">É um padrão que oculta a complexidade de uma ou mais classes por meio de uma facade (fachada), com o objetivo de simplificar uma interface e o acesso a mesma. Uma definição mais oficial do padrão facade é “O Padrão Facade fornece uma interface unificada para um conjunto de interfaces em um subsistema. O Facade define uma interface de nível mais alto que facilita a utilização do subsistema”.</p>

### Uso no projeto e justificativa
<p align="justify">No nosso projeto, a lógica de funcionamento de cada classe se encontra dentro das controllers correspondentes a cada model. Entretanto, foi feita uma separação das controllers e suas rotas, visando uma maior facilidade, já que a parte responsável pelas rotas possui uma grande simplicidade e delega o trabalho mais robusto às funções que estão nas controllers.</p>

*Rotas de produto*
    
## Flyweight

### Uso no projeto e justificativa

## Proxy

### Uso no projeto e justificativa

## Referências Bibliográficas

**Adapter Pattern.** Disponível em: https://springframework.guru/gang-of-four-design-patterns/adapter-pattern/. Acesso em: 08 de abril de 2021.

**Composite Pattern.** Disponível em: https://springframework.guru/gang-of-four-design-patterns/composite-pattern/. Acesso em: 08 de abril de 2021.

## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|07/03/2021|1.0|Adiciona estrutura inicial de gofs estruturais e resumo sobre facade|[Gabrielle Ribeiro](https://github.com/Gabrielle-Ribeiro)|
|08/03/2021|1.1|Adiciona resumo sobre Builder|[Rafael Ribeiro](https://github.com/rafaelflarrn)| 
|08/03/2021|1.2|Adiciona resumo sobre Composite|[Rafael Ribeiro](https://github.com/rafaelflarrn)|

