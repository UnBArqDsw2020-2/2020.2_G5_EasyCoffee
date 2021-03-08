# Product Backlog

<p align="justify">O Product Backlog é uma lista que contém todas as funções exigidas pelo produto. O Product Backlog não está necessariamente completo no início do projeto. O conteúdo desta lista é definido de acordo com os requisitos do projeto. Primeiro, você pode começar com o mais óbvio. Com o tempo, conforme você aprende mais sobre o produto e seus usuários, a lista de tarefas do produto continuará a crescer e mudar.</p>

## MoSCoW
<p align="justify">O método MoSCoW é uma técnica de priorização simples, mas eficaz, para o gerenciamento e organização eficaz de recursos.</p>

<p align="justify">A técnica MoSCoW foi projetada para ajudar a selecionar e priorizar no contexto do desenvolvimento de software. As letras maiúsculas são as siglas para Must have (deve ter), Should have (deveria ter), Could have "pode ​​ter" e Won’t have (não será feito,por enquanto) e são compostas de quatro categorias usadas para organizar requisitos, histórias de usuário ou necessidades.</p>

## Backlog do Produto Easy Coffee - V1.7

Foram feitas alterações no Backlog do Produto apresentado anteriormente. Foi acrescentado uma nova história de usuário. Além disso, foi feita a repriorização utilizando o MoSCoW e a pontuação das histórias utilizando o planning poker. 

A versão anterior pode ser encontrada em: [Backlog do Produto Easy Coffee - V1.6](entrega1/backlog.md)

## Lista de tarefas do produto - V1.7
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRRgY3mofb3Li3H3MoZzFwexJxMgmWK92AKN4QQrS01jkfF68fDlOka8k-vbN6cXHoZMArZXCBKPLnP/pubhtml?widget=true&amp;headers=false" width="670" height="680" frameborder="0"></iframe>

## História de usuário
<p align="justify">As histórias de usuário são ferramentas para o desenvolvimento ágil de software, que podem capturar a descrição dos recursos de software da perspectiva dos usuários finais.</p>

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
* [RF11](../entrega1/requisitos.md) via Brainstorm e Storyboard.

**US02 - Eu, como cliente, quero visualizar as informações sobre um determinado produto.**

*Tarefas*

* O sistema deve ser capaz de trazer as informações do produto de acordo com a página "comprar-cafe" de acordo com o [protótipo](https://trabalhofga123.wixsite.com/easycoffee/comprar-cafe).
* O sistema deve trazer as informações correspondentes do produto quando o usuário clicar sobre ele.

*Critérios de aceitação:*

* O cliente deve ser capaz de visualizar as informações do produto.

*Requisitos relacionados à história:*
* [RF12](../entrega1/requisitos.md) via Brainstorm, Storyboard e Questionário.
* [RF13](../entrega1/requisitos.md) via Brainstorm e Questionário.


**US03 - Eu, como cliente, quero vizualizar os produtos por categorias.**

*Tarefas*

* Criação da página "menus" de acordo com o [protótipo](https://trabalhofga123.wixsite.com/easycoffee/menus).
* O sistema de ser capaz de separar os produtos por categorias.

*Critérios de aceitação:*

* O cliente deve ser capaz de navegar com facilidade pelas categorias.
* O cliente deve ser capaz de visualizar todos os produtos desponíveis para compra de acordo com as suas categorias.
* O site deve ser responsivo para facilitar a navegação em diferentes aparelhos.

*Requisitos relacionados à história:*
* [RF07](../entrega1/requisitos.md) via Brainstorm.

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
* [RF03](../entrega1/requisitos.md) via Brainstorm e Storyboard.
* [RF07](../entrega1/requisitos.md) via Brainstorm.
* [RF08](../entrega1/requisitos.md) via Brainstorm.

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
* [RF04](../entrega1/requisitos.md) via Brainstorm.
* [RF07](../entrega1/requisitos.md) via Brainstorm.
* [RF09](../entrega1/requisitos.md) via Brainstorm.
* [RF10](../entrega1/requisitos.md) via Brainstorm.

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
* [RF30](../entrega1/requisitos.md) via Brainstorm e Questionário.

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
* [RF05](../entrega1/requisitos.md) via Brainstorm.

**US08 - Eu, como administrador, quero visualizar os produtos cadastados.**

*Tarefas*

* Criação de página "visualizar-produto-administrador".

*Critérios de aceitação:*
* O administrador do sistema deve ser capaz de visualizar os produtos cadastrados.
* O administrador deve estar logado para acessar essa página.
* Essa página deverá conter a opção de editar, excluir e colocar um produto em promoção (botões).

*Requisitos relacionados à história:* 
* [RF06](../entrega1/requisitos.md) via Brainstorm.

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
* [RF20](../entrega1/requisitos.md) via Brainstorm.

**US10 - Eu, como cliente, quero visualizar as avaliações de um produto feitas por outros clientes.**

*Tarefas*
* O cliente deve ser capaz de ver a avaliação na tela do produto.


*Critérios de aceitação:*

* O cliente do sistema deve ser capaz de ver a avaliação dos produtos.

*Requisitos relacionados à história:*
* [RF21](../entrega1/requisitos.md) via Brainstorm.

**US11 - Eu, como administrador, quero visualizar as avaliações de um produto feitas pelos clientes.**

*Tarefas*

* O administrador deve ser capaz de ver a avaliação na tela do produto.


*Critérios de aceitação:*

* O administrador do sistema deve ser capaz de de ver a avaliação dos produtos feita pelos os clientes.

*Requisitos relacionados à história:*
* [RF21](../entrega1/requisitos.md) via Brainstorm.

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
* [RF14](../entrega1/requisitos.md) via Brainstorm.

**US13 - Eu, como cliente, quero excluir produtos no carrinho de compras.**

*Tarefas*

* A tela de "carrinho" deve ser desenvolvido como está no protótipo.
* O usuário deve ser capaz de excluir o produto do carrinho.

*Critérios de aceitação:*

* O cliente de ser capaz de excluir o produto no carrinho.
* O cliente deve estar logado no sistema.

*Requisitos relacionados à história:*
* [RF15](../entrega1/requisitos.md) via Brainstorm.

#### Feature: Pagamento

**US14 - Eu, como cliente, quero editar a quantidade de um determinado produto no carrinho de compras.**

*Tarefas*

* O cliente deve ser capaz de alterar a quantidade de produtos no carrinho.
* A tela de edição deve ser feita como planejado no protótipo.

*Critérios de aceitação:*

* O cliente deve ser capaz de aditar seu carrinho.
* O cliente deve estar logado no sistema.

*Requisitos relacionados à história:*
* [RF14](../entrega1/requisitos.md) via Brainstorm.

**US15 - Eu, como cliente, quero realizar compra de produtos.**

*Tarefas*

* O cliente deve ser capaz de selecionar os produtos e adicionar ao carrinho.
* A tela onde os produtos estão listados deve ser feita em conformidade com o protótipo.

*Critérios de aceitação:*

* O cliente pode adicionar corretamente seus produtos ao carrinho. 
* o cliente deve estar logado em sua conta.

*Requisitos relacionados à história:*
* [RF16](../entrega1/requisitos.md) via Brainstorm.

**US16 - Eu, como administrador, quero cadastrar informações a respeito do frete.**

*Tarefas*

* O administrador do sistema deve ser capaz de cadastrar informações sobre o preço do frete.
* A tela onde o frete é cadastrado deve ser feita em conformidade com o protótipo.

*Critérios de aceitação:*

* O administrador pode adicionar corretamente as informações sobre o frete dos produtos. 
* Apenas o administrador logado em sua conta pode cadastrar informações sobre o frete.

*Requisitos relacionados à história:*
* [RF23](../entrega1/requisitos.md) via Brainstorm.

**US17 - Eu, como cliente, quero visualizar informações a respeito do frete.**

*Tarefas*

* O cliente deve ser capaz de visualizar informações sobre o frete de seus produtos.
* A tela onde o frete é mostrado deve ser feita em conformidade com o protótipo.

*Critérios de aceitação:*

* O cliente deve ver as informações sobre o frete apenas de seus produtos. 
* O cliente logado em sua conta para visualizar informações sobre o frete.


*Requisitos relacionados à história:*
* [RF24](../entrega1/requisitos.md) via Brainstorm.

**US18 - Eu, como cliente, quero fazer o pagamento dos produtos selecionados**

*Tarefas*

* O cliente deve ser capaz de fazer o pagamento de seus produtos.
* A tela de pagamentos deve ser feita em conformidade com o protótipo.

*Critérios de aceitação:*

* O cleinte deve ser capaz de pagar os produtos do carrinho. 
* Apenas o usuário e o administrador devem ter acesso aos dados da compra.


*Requisitos relacionados à história:*
* [RF17](../entrega1/requisitos.md) via Brainstorm e Questionário.

#### Feature: Acompanhamento do Pedido
**US19 - Eu, como cliente, quero acompanhar um pedido de uma compra.**

*Tarefas*

* A tela de acompanhamento desenvolvido como está no [protótipo](https://trabalhofga123.wixsite.com/easycoffee/comprar-cafe).

* O usuário deve ser capaz de acompanhar o status do seu pedido

  

*Critérios de aceitação:*

  

* Deve ser seguindo o padrão MVC

* O site deve ser responsivo para facilitar a navegação em diferentes aparelhos.

  

*Requisitos relacionados à história:*

* [RF18](../entrega1/requisitos.md) via Brainstorm e Storyboard.



**US20 - Eu, como administrador, quero atualizar o status de uma compra.**

  

*Tarefas*

  

* A tela de acompanhamento desenvolvido como está no protótipo [protótipo](https://trabalhofga123.wixsite.com/easycoffee/comprar-cafe).

* O administrador deve ser capaz de acompanhar a chegada de pedido e atualizar o status de acordo com o evoluir do pedido

  

*Critérios de aceitação:*

  

* Deve ser seguindo o padrão MVC

* O site deve ser responsivo para facilitar a navegação em diferentes aparelhos.

  

*Requisitos relacionados à história:*

* [RF18](../entrega1/requisitos.md),[ RF25](../entrega1/requisitos.md) via Brainstorm e Storyboard.

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

* [RF01](../entrega1/requisitos.md) via Brainstorm e Storyboard.

**US22 - Eu, como cliente, quero editar meu cadastro no site.**

  

*Tarefas*

  

* A tela de acompanhamento desenvolvido como está no [protótipo](https://trabalhofga123.wixsite.com/easycoffee/comprar-cafe).

* O cliente de ser capaz de fazer edições nos seus dados cadastrais, para manter sempre atualizado
  

*Critérios de aceitação:*

  

* Deve ser seguindo o padrão MVC

* O site deve ser responsivo para facilitar a navegação em diferentes aparelhos.

  

*Requisitos relacionados à história:*

* [RF01](../entrega1/requisitos.md) via Brainstorm e Storyboard.

**US23 - Eu, como cliente, quero visualizar meu cadastro no site.**

*Tarefas*

  

* A tela de acompanhamento desenvolvido como está no [protótipo](https://trabalhofga123.wixsite.com/easycoffee/comprar-cafe).

* O cliente de ser capaz visualizar seus dados.
  

*Critérios de aceitação:*

  

* Deve ser seguindo o padrão MVC

* O site deve ser responsivo para facilitar a navegação em diferentes aparelhos.


**US24 - Eu, como cliente, quero excluir meu cadastro no site.**

  

*Tarefas*

  

* A tela de acompanhamento desenvolvido como está no [protótipo](https://trabalhofga123.wixsite.com/easycoffee/comprar-cafe).

* O cliente de ser capaz de ter alguma forma de excluir seu perfil.
  

*Critérios de aceitação:*

  

* Deve ser seguindo o padrão MVC

* O site deve ser responsivo para facilitar a navegação em diferentes aparelhos.

  

*Requisitos relacionados à história:*

* [RF01](../entrega1/requisitos.md) via Brainstorm e Storyboard.

#### Feature: Login

**US25 - Eu, como administrador, quero fazer login na aplicação.**

*Tarefas:*

* Utilizar token JWT para manter a sessão salva, caso o usuário feche a aba.
* Diferenciar permissões entre administrador e usuário comum.
* Salvar os dados do administrador em sua conta antes da sessão ser finalizada.

*Critérios de aceitação:*

* Administrador deve ter permissões especiais
* Usuários comuns não podem ter permissões de administrador
* Deve ser determinado um tempo para a sessão ser esgotada
* Definir critérios de criação de conta, ex.: senha mínimo 6 dígitos incluindo ao menos uma letra maiúscula e um número.

*Requisitos relacionados à história:*

* [RF02](../entrega1/requisitos.md) via Brainstorm e Storyboard.

**US26 - Eu, como cliente, quero fazer login na aplicação.**
*Tarefas:*
* Utilizar token JWT para manter a sessão salva, caso o usuário feche a aba.
* Diferenciar permissões entre administrador e usuário comum.
* Salvar os dados do usuário em sua conta antes da sessão ser finalizada.

*Critérios de aceitação:*

* Usuários comuns não podem ter permissões de administrador
* Deve ser determinado um tempo para a sessão ser esgotada
* Definir critérios de criação de conta, ex.: senha mínimo 6 dígitos incluindo ao menos uma letra maiúscula e um número.

*Requisitos relacionados à história:*
* [RF02](../entrega1/requisitos.md) via Brainstorm e Storyboard.

### Épico 4: Área de Usuário

#### Feature: Área do Administrador

**US27 - Eu, como administrador, quero adicionar informações a um glossário sobre café.**

*Tarefas:*

* Criar estrutura, uma espécie de formulário, padronizada para adicionar as informações em um padrão comum.
* Linkar as informações ao respectivo glossário.

*Critérios de aceitação:*

* Não devem haver informações duplicadas.
* A informação adicionada deve ser linkada ao glossário correto.

*Requisitos relacionados à história:*

* [RF26](../entrega1/requisitos.md) via Brainstorm e Storyboard.

**US28 - Eu, como administrador, quero editar informações em um glossário sobre café.**

*Tarefas:*

* Implementar funcionalidade editar visível somente aos administradores
* Recuperar do Banco de Dados o glossário correspondente
* Atualizar somente as informações editadas
* Após edição atualizar a lista de glossários

*Critérios de aceitação:*

* Todos os dados editados devem ser persistidos
* Somente administradores podem editar um glossário
* O glossário editado deve aparecer com as novas informações junto aos outros.

*Requisitos relacionados à história:*

* [RF27](../entrega1/requisitos.md) via Brainstorm e Storyboard.

**US29 - Eu, como administrador, quero excluir informações de um glossário sobre café.**

*Tarefas:*

* Implementar funcionalidade excluir visível somente aos administradores
* Após a exclusão atualizar a lista de glossários

*Critérios de aceitação:*

* Somente administradores podem excluir um glossário.
* O glossário excluído não deve aparecer junto aos outros após a exclusão.

*Requisitos relacionados à história:*

* [RF28](../entrega1/requisitos.md) via Brainstorm e Storyboard.

**US30 - Eu, como administrador, quero visualizar informações no glossário sobre café.**

*Tarefas*

* Recuperar do Banco de Dados o glossário sobre café.

* O administrador deve ter acesso as informações contidas no glossário.
  

*Critérios de aceitação:*

  

* Acesso as informações que estão no glossário

  

*Requisitos relacionados à história:*

* [RF29](../entrega1/requisitos.md) via Brainstorm e Storyboard.


#### Feature: Área do Cliente


**US31 - Eu, como cliente, quero acessar o meu histórico de produtos comprados anteriormente.**

  

*Tarefas*

  

* Guardar no banco os dados de compras do cliente.

* Recuperar do Banco de Dados os dados de compras anteriores.

* Implementar uma área de fácil acesso ao histórico de compras.
  

*Critérios de aceitação:*

  

* Cada usuário possui um histórico personalizado de produtos comprados anteriormente.

* Não deve haver produtos duplicados.

* Deve permitir a compra de maneira facilitada.
  

*Requisitos relacionados à história:*

* [RF19](../entrega1/requisitos.md) via Brainstorm.


**US32 - Eu, como cliente, quero marcar um produto como favorito.**

  

*Tarefas*

  

* Implementar funcionalidade em que o usuário possa marcar marque produtos como favoritos.

* Guardar no Banco de Dados uma lista com os produtos favoritos.
  

*Critérios de aceitação:*

  

* Permitir adicionar produtos a lista de favoritos.

* Permitir remover produtos da lista de favoritos.

* Deve permitir a compra de maneira facilitada.
  

*Requisitos relacionados à história:*

* [RF22](../entrega1/requisitos.md) via Brainstorm.


**US33 - Eu, como cliente, quero visualizar meus produtos marcados como favoritos.**

  

*Tarefas*

  

* Recuperar do Banco de Dados a lista de produtos favoritos referente ao usuário.

* Disponibilizar uma área destinada aos produtos favoritos.
  

*Critérios de aceitação:*

  

* Visualizar de forma ordenada a lista de favoritos

* Não deve haver produtos duplicados.

* Deve permitir a compra de maneira facilitada.
  

*Requisitos relacionados à história:*

* [RF22](../entrega1/requisitos.md) via Brainstorm.


**US34 - Eu, como cliente, quero visualizar informações no glossário sobre café.**

  

*Tarefas*

  

* Recuperar do Banco de Dados o glossário sobre café.

* O usuário deve ter acesso as informações contidas no glossário.
  

*Critérios de aceitação:*

  

* Acesso as informações que estão no glossário sobre café
  

*Requisitos relacionados à história:*

* [RF29](../entrega1/requisitos.md) via Brainstorm e Storyboard.


## Referência Bibliográficas

- Backlog de Produto: o que é e como construir passo a passo, INCUCA. 
Disponível em:https://incuca.net/backlog-de-produto-o-que-e-e-como-construir-passo-a-passo/#:~:text=Em%20uma%20metodologia%20%C3%A1gil%20como,Backlog%20do%20time%20de%20desenvolvimento. 
Acesso em: 17 fev 2021.

- Epic, Feature e User Story (Epico, Funcionalidade e História de Usuário), Até o Momento. 
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
|18/02/2021|1.4| Adição das US14 a US18|[Gustavo Afonso](https://github.com/GustavoAPS)|
|18/02/2021|1.5| Adição das US24 a US28|[Maicon Mares](https://github.com/MaiconMares)|
|18/02/2021|1.6| Adição da descrição MoSCoW|[Iago Theóphilo](https://github.com/iagotheophilo)|
|04/03/2021|1.7| Repriorização do Backlog e pontuação com planning poker | [Danilo Domingo](https://github.com/danilow200), [Gabrielle Ribeiro](https://github.com/Gabrielle-Ribeiro), [Gustavo Afonso](https://github.com/GustavoAPS), [Iago Theóphilo](https://github.com/IagoTheophilo), [Itallo Gravina](https://github.com/itallogravina), [Maicon Mares](https://github.com/MaiconMares), [Rafael Ribeiro](https://github.com/rafaelflarrn)|
|08/03/2021|1.7|Adiciona explicações sobre o backlog|[Gabrielle Ribeiro](https://github.com/Gabrielle-Ribeiro)|
|08/03/2021|1.7|Corrige nome das Us e corrige erros|[Gustavo Afonso](https://github.com/GustavoAPS)|
|08/03/2021|1.7|Adiciona tarefas da US23 e adciona link nas RFs|[Danilo Domingo](https://github.com/danilow200)|
