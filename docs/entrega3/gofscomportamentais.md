# GoFs Comportamentais

## Interpreter

### Uso no projeto e justificativa

## Template Method

### Uso no projeto e justificativa

## Chain of Responsibility

<p align="justify">É um padrão que dá a oportunidade a mais de um objeto de lidar com uma solicitação. Isso significa que uma mesma solicitação passa por uma série de objetos em cadeia (objetos receptores e objetos de solicitação), até que algum seja capaz de tratar a solicitação. Uma vantagem no uso desse padrão é evitar a dependência entre um objeto receptor e um objeto solicitante. </p>

### Uso no projeto e justificativa

<p align="justify">O NodeJS em conjunto com a API Express faz uso de funções chamadas Middleware. Essas funções têm acesso ao objeto de requisição (req), o objeto de resposta (res), e a próxima função de middleware (next) dentro do ciclo de solicitação-resposta da aplicação. </p>

<p align="justify">As funções middleware podem executar qualquer código, fazer mudanças nos objetos de solicitação e resposta, encerrar o ciclo de solicitação-resposta e chamar o próximo middleware na fila. </p>

*Middleware de autenticação de usuário*
    
<p align="justify">No nosso projeto, foi feito o uso de middleware na autenticação do usuário, para assegurar que só terá acesso a determinadas funcionalidades do site o usuário que possuir conta em nosso sistema e estiver devidamente logado. </p>

## Command

### Uso no projeto e justificativa

## Iterator 

<p align="justify">É um padrão que possibilita percorrer uma coleção de objetos, sem que o encapsulamento dos mesmos seja violado.</p>

### Uso no projeto e justificativa

## Mediator

### Uso no projeto e justificativa

## Memento

<p align="justify">É um padrão que armazena o estado de um objeto em um dado momento, permitindo a volta para esse estado caso alguma alteração seja feita.</p>

### Uso no projeto e justificativa

## Observer

### Uso no projeto e justificativa

## State
<p align="justify">É um padrão que faz com que um objeto altere o seu comportamento quando o seu estado interno mudar. O objeto irá aparentar mudar de classe.</p>

### Uso no projeto e justificativa

## Strategy

### Uso no projeto e justificativa

## Visitor

### Uso no projeto e justificativa

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|07/03/2021|1.0|Adiciona estrutura inicial de gofs comportamentais e chain of responsibility|[Gabrielle Ribeiro](https://github.com/Gabrielle-Ribeiro)|
|07/03/2021|1.0|Adiciona Resumo sobre iteretor e memento|[Gustavo Afonso](https://github.com/GustavoAPS)|
|07/03/2021|1.0|Adiciona Resumo sobre State|[Iago Theóphilo](https://github.com/iagotheophilo)|