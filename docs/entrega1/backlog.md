# Product Backlog
O Product Backlog é uma lista que contém todas as funções exigidas pelo produto. O Product Backlog não está necessariamente completo no início do projeto. O conteúdo desta lista é definido de acordo com os requisitos do projeto. Primeiro, você pode começar com o mais óbvio. Com o tempo, conforme você aprende mais sobre o produto e seus usuários, a lista de tarefas do produto continuará a crescer e mudar.

## Lista de tarefas do produto 
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTL-oLfNTjfTdGJdOC-h-qVVj5wFxx-4JpZy7EoWlZNCGP65qADNpT3o7-DNrqrbBdsJpa1iV2ZD8V1/pubhtml?gid=0&single=true&widget=false&headers=false&gridlines=false&chrome=false" width="670" height="680" frameborder="0"></iframe>

## História de usuário
As histórias de usuário são ferramentas para o desenvolvimento ágil de software, que podem capturar a descrição dos recursos de software da perspectiva dos usuários finais.

### Épico 1:  Produto

#### Feature: Listar

**US01 - Eu, como cliente, quero vizualizar os produtos do site, para saber o que está disponível para compra**

*Tarefas*

* Criação da página "comprar-cafe" de acordo com o [protótipo](https://trabalhofga123.wixsite.com/easycoffee/comprar-cafe).
* O sistema de ser capaz de trazer os produtos disponibilizados pelo administrador do sistema contendo o nome do produto e seu valor.

*Critérios de aceitação:*

* O cliente deve ser capaz de navegar com facilidade pelos produtos.
* O cliente deve ser capaz de visualizar todos os produtos desponíveis para compra.
* O site deve ser responsivo para facilitar a navegação em diferentes aparelhos.

*Requisitos relacionados à história:*
* [RF11]() via Brainstorm e Storyboard.

**US02 - Eu, como cliente, quero visualizar as informações sobre um determinado produto.**

*Tarefas*

* O sistema deve ser capaz de trazer as informações do produto de acordo com a página "comprar-cafe" de acordo com o [protótipo](https://trabalhofga123.wixsite.com/easycoffee/comprar-cafe).
* O sistema deve trazer as informações correspondentes do produto quando o usuário clicar sobre ele.

*Critérios de aceitação:*

* O cliente deve ser capaz de visualizar as informações do produto.

*Requisitos relacionados à história:*
* [RF12]() via Brainstorm, Storyboard e Questionário.
* [RF13]() via Brainstorm e Questionário.


**US03 - Eu, como cliente, quero vizualizar os produtos por categorias.**

*Tarefas*

* Criação da página "menus" de acordo com o [protótipo](https://trabalhofga123.wixsite.com/easycoffee/menus).
* O sistema de ser capaz de separar os produtos por categorias.

*Critérios de aceitação:*

* O cliente deve ser capaz de navegar com facilidade pelas categorias.
* O cliente deve ser capaz de visualizar todos os produtos desponíveis para compra de acordo com as suas categorias.
* O site deve ser responsivo para facilitar a navegação em diferentes aparelhos.

*Requisitos relacionados à história:*
* [RF07]() via Brainstorm.

#### Feature: Manter Produto

**US04 - Eu, como administrador, quero cadastrar produtos no site.**

*Tarefas*

* Criação da página "cadastrar-produto".
* O sistema de ser capaz de salvar os produtos criados.
* Quando o sistema salvar o produto deve ser apresentado a mensagem "Produto cadastrado com sucesso.".


*Critérios de aceitação:*

* O administrador do sistema deve ser capaz de cadastrar produtos.
* O administrador deve estar logado para cadastrar o produto.
* Depois de cadastrar o produto, ele deve ser disponibilizado para compra.

*Requisitos relacionados à história:*
* [RF03]() via Brainstorm e Storyboard.
* [RF07]() via Brainstorm.
* [RF08]() via Brainstorm.

**US05 - Eu, como administrador, quero editar produtos no site.**

*Tarefas*

* Criação da página "editar-produto".
* O sistema deve ser capaz de editar as informações de produtos cadastrados no site.
* Antes das alterações serem salvas, deve ser apresentado uma mensagem de confirmação.
* Quando o sistema salvar as alterações do produto deve ser apresentado a mensagem "Produto editado com sucesso.".

*Critérios de aceitação:*

* O administrador do sistema deve ser capaz de editar produtos.
* O administrador deve estar logado para editar um produto.
* Antes do produto ter a alteração salva, deve ser apresentado uma mensagem de confirmação.
* Depois de editar um produto, ele deve ter suas informações atualizadas para compra.

*Requisitos relacionados à história:* 
* [RF04]() via Brainstorm.
* [RF07]() via Brainstorm.
* [RF09]() via Brainstorm.
* [RF10]() via Brainstorm.

**US06 - Eu, como administrador, quero colocar um produto em promoção.**

*Tarefas*

* Criação de opção de colocar um produto em promoção na página "visualizar-produto-administrador".
* Criação de página "colocar-produto-em-promoçao".
* O sistema deve ser capaz de colocar um produto em promoção.
* Antes das alterações serem salvas, deve ser apresentado uma mensagem de confirmação.
* Quando o sistema colocar o produto em promoção, deve ser apresentado a mensagem "Produto colocado em promoção com sucesso.".

*Critérios de aceitação:*

* O administrador do sistema deve ser capaz de colocar um produto em promoção.
* O administrador deve estar logado para colocar um produto em promoção.
* Antes do produto ter a alteração salva, deve ser apresentado uma mensagem de confirmação.
* Depois de colocar um produto em promoção, ele deve ter suas informações atualizadas para compra.

*Requisitos relacionados à história:* 
* [RF30]() via Brainstorm e Questionário.

**US07 - Eu, como administrador, quero excluir produtos no site.**

*Tarefas*

* Criação de botão de excluir produto na página de "visualizar-produto-administrador".
* O sistema deve ser capaz de excluir um produto.
* Antes do produto ser excluído, deve ser apresentado uma mensagem de confirmação.
* Quando o sistema excluir um produto, deve ser apresentado a mensagem "Produto excluído com sucesso.".

*Critérios de aceitação:*
* O administrador do sistema deve ser capaz de excluir um produto.
* O administrador deve estar logado para excluir um produto.
* Deve existir uma mensagem de confirmação, antes de um produto ser excluído.
* Depois de excluir um produto , ele deve desaparecer para compra.

*Requisitos relacionados à história:* 
* [RF05]() via Brainstorm.

**US08 - Eu, como administrador, quero visualizar os produtos cadastados.**

*Tarefas*

* Criação de página "visualizar-produto-administrador".

*Critérios de aceitação:*
* O administrador do sistema deve ser capaz de visualizar os produtos cadastrados.
* O administrador deve estar logado para acessar essa página.
* Essa página deverá conter a opção de editar, excluir e colocar um produto em promoção (botões).

*Requisitos relacionados à história:* 
* [RF06]() via Brainstorm.

#### Feature: Avaliação

**US09 - Eu, como cliente, quero avaliar um produto comprado.**
*Tarefas*

* Criação da página "avaliar-compra".
* O sistema de ser capaz de salvar a avaliação feita.
* Quando o sistema salvar a avaliação de ser apresentado a mensagem "Avaliação feita com sucesso."

*Critérios de aceitação:*

* O cliente do sistema deve ser capaz de avaliar produtos.
* O cliente deve estar logado para avaliar o produto.
* Depois de avaliar o produto deve ser possivel ver a avaliação.

*Requisitos relacionados à história:*
* [RF20]() via Brainstorm.

**US10 - Eu, como cliente, quero visualizar as avaliações de um produto feitas por outros clientes.**

*Tarefas*
* O cliente deve ser capaz de ver a avaliação na tela do produto.


*Critérios de aceitação:*

* O cliente do sistema deve ser capaz de ver a avaliação dos produtos.

*Requisitos relacionados à história:*
* [RF21]() via Brainstorm.

**US11 - Eu, como administrador, quero visualizar as avaliações de um produto feitas pelos clientes.**

*Tarefas*

* O administrador deve ser capaz de ver a avaliação na tela do produto.


*Critérios de aceitação:*

* O administrador do sistema deve ser capaz de de ver a avaliação dos produtos feita pelos os clientes.

*Requisitos relacionados à história:*
* [RF21]() via Brainstorm.

### Épico 2: Área de Compras

#### Feature: Carrinho de Compras

**US12 - Eu, como cliente, quero adicionar produtos no carrinho de compras.**

*Tarefas*

* Na tela de "comprar-produto" deve ser capaz de adicionar o produto no carrinho como está no protótipo.
* O usuário deve ser capaz de adicionar o produto ao carrinho.

*Critérios de aceitação:*

* O cliente de ser capaz de adcionar o produto no carrinho com a quantidade informada.
* O cliente deve estar logado no sistema.

*Requisitos relacionados à história:*
* [RF14]() via Brainstorm.

**US13 - Eu, como cliente, quero excluir produtos no carrinho de compras.**

*Tarefas*

* A tela de "carrinho" deve ser desenvolvido como está no protótipo.
* O usuário deve ser capaz de excluir o produto do carrinho.

*Critérios de aceitação:*

* O cliente de ser capaz de excluir o produto no carrinho.
* O cliente deve estar logado no sistema.

*Requisitos relacionados à história:*
* [RF15]() via Brainstorm.

#### Feature: Pagamento


#### Feature: Acompanhamento do Pedido
**US19 - Acompanhar um pedido de uma compra, como cliente**

  

*Tarefas*

  

* A tela de acompanhamento desenvolvido como está no [protótipo](https://trabalhofga123.wixsite.com/easycoffee/comprar-cafe).

* O usuário deve ser capaz de acompanhar o status do seu pedido

  

*Critérios de aceitação:*

  

* Deve ser seguindo o padrão MVC

* O site deve ser responsivo para facilitar a navegação em diferentes aparelhos.

  

*Requisitos relacionados à história:*

* [RF18]() via Brainstorm e Storyboard.



**US20 - Acompanhar um pedido de uma compra, como administrador**

  

*Tarefas*

  

* A tela de acompanhamento desenvolvido como está no protótipo [protótipo](https://trabalhofga123.wixsite.com/easycoffee/comprar-cafe).

* O administrador deve ser capaz de acompanhar a chegada de pedido e atualizar o status de acordo com o evoluir do pedido

  

*Critérios de aceitação:*

  

* Deve ser seguindo o padrão MVC

* O site deve ser responsivo para facilitar a navegação em diferentes aparelhos.

  

*Requisitos relacionados à história:*

* [RF18](),[ RF25]() via Brainstorm e Storyboard.

### Épico 3: Acesso a Aplicação

#### Feature: Manter Cliente
**US21 - Eu, como cliente, quero realizar meu cadastro no site.**

  

*Tarefas*

  

* A tela de acompanhamento desenvolvido como está no [protótipo](https://trabalhofga123.wixsite.com/easycoffee/comprar-cafe).

* O cliente de ser capaz de realizar seu cadastro sem nenhum problema preenchendo os campos necessários
  

*Critérios de aceitação:*

  

* Deve ser seguindo o padrão MVC

* O site deve ser responsivo para facilitar a navegação em diferentes aparelhos.

  

*Requisitos relacionados à história:*

* [RF01]() via Brainstorm e Storyboard.

**US22 - Eu, como cliente, quero editar meu cadastro no site.**

  

*Tarefas*

  

* A tela de acompanhamento desenvolvido como está no [protótipo](https://trabalhofga123.wixsite.com/easycoffee/comprar-cafe).

* O cliente de ser capaz de fazer edições nos seus dados cadastrais, para manter sempre atualizado
  

*Critérios de aceitação:*

  

* Deve ser seguindo o padrão MVC

* O site deve ser responsivo para facilitar a navegação em diferentes aparelhos.

  

*Requisitos relacionados à história:*

* [RF01]() via Brainstorm e Storyboard.


**US23 - Eu, como cliente, quero excluir meu cadastro no site.**

  

*Tarefas*

  

* A tela de acompanhamento desenvolvido como está no [protótipo](https://trabalhofga123.wixsite.com/easycoffee/comprar-cafe).

* O cliente de ser capaz de ter alguma forma de excluir seu perfil.
  

*Critérios de aceitação:*

  

* Deve ser seguindo o padrão MVC

* O site deve ser responsivo para facilitar a navegação em diferentes aparelhos.

  

*Requisitos relacionados à história:*

* [RF01]() via Brainstorm e Storyboard.






#### Feature: Login

### Épico 4: Área de Usuário

#### Feature: Área do Administrador





**US29 - Eu, como administrador, quero visualizar informações no glossário sobre café.**

  
*Tarefas*

  

* Recuperar do Banco de Dados o glossário sobre café.

* O administrador deve ter acesso as informações contidas no glossário.
  

*Critérios de aceitação:*

  

* Acesso as informações que estão no glossário

  

*Requisitos relacionados à história:*

* [RF29]() via Brainstorm e Storyboard.


#### Feature: Área do Cliente


**US30 - Eu, como cliente, quero acessar o meu histórico de produtos comprados anteriormente.**

  

*Tarefas*

  

* Guardar no banco os dados de compras do cliente.

* Recuperar do Banco de Dados os dados de compras anteriores.

* Implementar uma área de fácil acesso ao histórico de compras.
  

*Critérios de aceitação:*

  

* Cada usuário possui um histórico personalizado de produtos comprados anteriormente.

* Não deve haver produtos duplicados.

* Deve permitir a compra de maneira facilitada.
  

*Requisitos relacionados à história:*

* [RF19]() via Brainstorm.


**US31 - Eu, como cliente, quero marcar um produto como favorito.**

  

*Tarefas*

  

* Implementar funcionalidade em que o usuário possa marcar marque produtos como favoritos.

* Guardar no Banco de Dados uma lista com os produtos favoritos.
  

*Critérios de aceitação:*

  

* Permitir adicionar produtos a lista de favoritos.

* Permitir remover produtos da lista de favoritos.

* Deve permitir a compra de maneira facilitada.
  

*Requisitos relacionados à história:*

* [RF22]() via Brainstorm.


**US32 - Eu, como cliente, quero visualizar meus produtos marcados como favoritos.**

  

*Tarefas*

  

* Recuperar do Banco de Dados a lista de produtos favoritos referente ao usuário.

* Disponibilizar uma área destinada aos produtos favoritos.
  

*Critérios de aceitação:*

  

* Visualizar de forma ordenada a lista de favoritos

* Não deve haver produtos duplicados.

* Deve permitir a compra de maneira facilitada.
  

*Requisitos relacionados à história:*

* [RF22]() via Brainstorm.


**US33 - Eu, como cliente, quero visualizar informações no glossário sobre café.**

  

*Tarefas*

  

* Recuperar do Banco de Dados o glossário sobre café.

* O usuário deve ter acesso as informações contidas no glossário.
  

*Critérios de aceitação:*

  

* Acesso as informações que estão no glossário sobre café
  

*Requisitos relacionados à história:*

* [RF29]() via Brainstorm e Storyboard.


## Referência Bibliográficas

- Backlog de Produto: o que é e como construir passo a passo, INCUCA. 
Disponível em:https://incuca.net/backlog-de-produto-o-que-e-e-como-construir-passo-a-passo/#:~:text=Em%20uma%20metodologia%20%C3%A1gil%20como,Backlog%20do%20time%20de%20desenvolvimento. 
Acesso em: 17 fev 2021.

- EPIC,FEATURE E USER STORY, ATÉ O MOMENTO. 
Disponível em:https://www.ateomomento.com.br/epic-feature-e-user-story/. 
Acesso em: 17 fev 2021.


## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|17/02/2021|1.0| Criação do Backlog do produto | [Danilo Domingo](https://github.com/danilow200), [Gabrielle Ribeiro](https://github.com/Gabrielle-Ribeiro), [Iago Theóphilo](https://github.com/IagoTheophilo)|
|17/02/2021|1.0|Product Backlog, História de usuário US01 até US04|[Iago Theóphilo](https://github.com/IagoTheophilo)|
|17/02/2021|1.1|Product Backlog, História de usuário US09 até US15|[Danilo Domingo](https://github.com/danilow200)|
|17/02/2021|1.2| Adição das US05 a US08 | [Gabrielle Ribeiro](https://github.com/Gabrielle-Ribeiro)|
|17/02/2021|1.3| Adição das US29 a US33 | [Rafael Ribeiro](https://github.com/rafaelflarrn)|