# Metodologia

<p align="justify">Diversos processos, metodologias e práticas foram apresentadas na disciplina de Arquitetura e Desenho de Software. O grupo Easy Coffee então criou uma metodologia híbrida própria, que inclui os aspectos dessas diversas metodologias que mais se adequam no contexto do nosso projeto e na realidade da nossa equipe. Além disso, o time não definiu papéis específicos, como algumas metodologias propõem. Ao invés disso, todos os membros têm uma posição de igualdade e contribuirão e terão responsabilidade com todas partes do projeto.  Devido à pandemia, todas as práticas que normalmente são feitas de forma presencial, serão feitas de forma remota, utilizando ferramentas de comunicação que suportam reuniões e compartilhamento de tela, como Microsoft Teams, Google Meets e Discord.</p>

<p align="justify">Os detalhes dessa metodologia híbrida e de onde cada prática, princípio e artefato foi retirado são encontrados a seguir:</p>

## XP

Os seguintes princípios e práticas da metodologia XP - eXtreme Programming foram adotados:

*Princípios:*

* **Comunicação**: Esse princípio será adotado visando a integração e a participação ativa dos membros da equipe. Com a impossibilidade de encontros presenciais, a comunicação será feita de forma online.

*Práticas:*

* **Equipe Integral**: é uma prática que visa a inserção e integração de todos os membros envolvidos no projeto. Valorizando reuniões e diálogos, para que todos sejam ouvidos e o projeto seja bem sucedido.
* **Pair Programming**: é uma prática que consiste em duas pessoas compartilhando o mesmo computador para programar. Enquanto um escreve código, o outro auxilia com sugestões. Além disso, são feitos revezamentos periódicos de quem estará codificando em um dado momento. Essa prática será adotada, porque ela estimula a comunicação (princípio do XP) e cria um ambiente para a troca de conhecimento e maior aprendizagem entre a equipe. 
* **Código Coletivo**: é uma prática que afirma que o código é propriedade de todos da equipe. Assim não é necessário pedir autorização de alguém para modificar algo. Essa prática será adotada porque dessa maneira todos poderão conhecer todas as partes do código. Isso irá contribuir para melhorias no código, através de refatoração. Além disso, isso se alinha com a decisão do grupo de não definir papéis e todos possuírem uma posição de igualdade. 
* **Baby Steps**: pequenas mudanças serão feitas no código por vez, de forma incremental. O foco estará apenas no que é necessário naquela etapa do projeto, e o software irá evoluir a cada iteração até chegar no produto final.
* **Padrão de codificação**: será definido um padrão para os códigos escritos, logo nas etapas iniciais do projeto, para que todos possam compreender códigos escritos por outros membros. Isso se faz extremamente importante, tendo em vista que a prática de código coletivo.
Refatoração: sempre que necessário serão feitas melhorias no código, sem alterações nas suas funcionalidades. Visando sempre um código de qualidade. 

## SCRUM

As seguintes práticas e artefatos da metodologia ágil SCRUM foram adotados:

*Práticas:*

* **Sprints:** o projeto será dividido em ciclos de uma semana, onde um conjunto determinado de atividades deverão ser realizadas. Dessa forma, o projeto será  desenvolvido de forma interativa, com pequenas entregas que agregam valor sendo feitas ao longo do tempo.
* **Sprint Planning:** É uma reunião que ocorre no início de cada Sprint, com o objetivo de decidir o que será feito e entregue durante aquela Sprint.
* **Sprint Retrospective:** após a reunião de Review, essa prática será utilizada para avaliar o que funcionou bem naquele sprint e o que pode ser melhorado, bem como que ações serão tomadas para que essas melhorias ocorram. 
* **Sprint Review:** é uma reunião que será realizada no fim de cada sprint, com o objetivo de verificar o que foi de fato cumprido durante aquela Sprint. 
* **Daily Scrum:** todos os dias será realizada uma pequena reunião, com o objetivo de manter todos os membros atualizados sobre o andamento do projeto. Nessa reunião, cada membro informará o que fez no dia anterior, o que pretende fazer no dia atual e quais são suas dificuldades.
* **Planning Poker:** É uma prática que será utilizada para estabelecer os objetivos de cada Sprint de forma colaborativa e utilizando estimativas. Será utilizada a ferramenta online: [PlanITpoker](https://www.planitpoker.com/) para realização dessa prática. 

*Artefatos:*

* **Product Backlog:** É um artefato que consiste em uma lista, que contém o que precisa ser feito. Nosso backlog do produto é composto por épicos, features, histórias de usuário, tarefas e critérios de aceitação. Nosso backlog pode ser encontrado aqui.
* **Sprint Backlog:** É um artefato que será utilizado para manter a lista de tarefas da Sprint que está sendo realizada.
* **Velocity:** É um artefato que será utilizado para identificarmos uma métrica que mostrará o que do Product Backlog foi de fato cumprido naquela Sprint. A equipe utilizará esse artefato para auxiliar a controlar o escopo dentro do tempo estipulado. 


## OpenUp

Os seguintes artefatos foram adotados do processo OpenUp:

*Artefatos:*

* **Léxico:** é um artefato, que traz o significado de termos específicos da linguagem de um determinado contexto. Tendo isso em vista, o grupo utilizará o léxico para apresentar alguns termos e palavras dentro do contexto de cafeterias. 
* **Protótipos:** o grupo utilizará esse artefato para validar os requisitos elicitados, bem como um auxílio na implementação desses requisitos e no desenvolvimento do nosso site.
* **Modelagem de dados:** Será utilizada para ajudar a visualizar as relações que existem no projeto, contribuindo no desenvolvimento do nosso software.
* **Documento de Visão:** É um documento que será utilizado para trazer uma apresentação do projeto e vários dos aspectos relacionados a este, de uma forma que qualquer pessoa, mesmo sem conhecimentos técnicos, seja capaz de entender. Nosso documento de visão pode ser encontrado [aqui](/entrega1/documento_de_visao.md).

## Quadro Kanban

É uma prática que nos auxiliará a manter o gerenciamento do fluxo de trabalho da equipe.
Para isso será utilizada a ferramenta Zenhub. Para poder visualizá-lo será necessário instalar a extensão do Zenhub para o seu navegador: [https://www.zenhub.com/extension](https://www.zenhub.com/extension).

## Testes Unitários
Teste unitário é basicamente o teste da menor parte testável de uma aplicação. Como por exemplo uma calculada simples, haverá um teste unitário para cada função dessa calculora( soma, subtração, multiplicação e divisão).

Serão utilizados testes unitários, para verificar se as funcionalidades implementadas funcionam como o esperado. Entretanto, devido a pouca experiência do grupo, essa prática será adaptada, tendo os testes escritos após a codificação da funcionalidade, e não antes como sugere o XP.


## Referências Bibliográficas

- eXtreme Programming. Disponível em: [http://www.extremeprogramming.org/](http://www.extremeprogramming.org/). Acesso em: 17/02/2021.
- Kanban. Disponível em: [https://artia.com/kanban/](https://artia.com/kanban/). Acesso em: 17/02/2021.
- OpenUp. Disponível em: [http://www.utm.mx/~caff/doc/OpenUPWeb/](http://www.utm.mx/~caff/doc/OpenUPWeb/). Acesso em: 17/02/2021.
- SCRUM. Disponível em: [https://www.desenvolvimentoagil.com.br/scrum/](https://www.desenvolvimentoagil.com.br/scrum/). Acesso em: 17/02/2021.
- Entenda de uma vez por todas o que são testes unitários, para que servem e como fazê-los. Disponível em: [https://dayvsonlima.medium.com/entenda-de-uma-vez-por-todas-o-que-s%C3%A3o-testes-unit%C3%A1rios-para-que-servem-e-como-faz%C3%AA-los-2a6f645bab3](https://dayvsonlima.medium.com/entenda-de-uma-vez-por-todas-o-que-s%C3%A3o-testes-unit%C3%A1rios-para-que-servem-e-como-faz%C3%AA-los-2a6f645bab3). Acesso em: 05/03/2021
- PlanITpoker. Disponível em: [https://www.planitpoker.com/](https://www.planitpoker.com/). Acesso em: 05/03/2021

## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|17/02/2021|0.5|Discussão de metodologia|[Danilo Domingo](https://github.com/danilow200), [Gabrielle Ribeiro](https://github.com/Gabrielle-Ribeiro), [Gustavo Afonso](https://github.com/GustavoAPS), [Iago Theóphilo](https://github.com/IagoTheophilo), [Itallo Gravina](https://github.com/itallogravina), [Maicon Mares](https://github.com/MaiconMares), [Rafael Ribeiro](https://github.com/rafaelflarrn)|
|18/02/2021|1.0|Adiciona metodologia|[Gabrielle Ribeiro](https://github.com/Gabrielle-Ribeiro)|
|05/03/2021|1.1|Adiciona testes unitários|[Danilo Domingo](https://github.com/danilow200)|
