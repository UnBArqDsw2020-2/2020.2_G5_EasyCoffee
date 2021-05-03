# Documento de Arquitetura de Software

## 1. Introdução

#### **1.1. Finalidade**
Este documento oferece uma visão geral arquitetural abrangente do sistema, usando diversas visões arquiteturais para representar diferentes aspectos do sistema. O objetivo deste documento é capturar e comunicar as decisões arquiteturais significativas que foram tomadas em relação ao sistema.

#### **1.2. Escopo**

#### **1.3. Definições, Acrônimos e Abreviações**

#### **1.4. Referências Bibliográficas**

#### **1.5. Visão Geral**

## 2. Representação Arquitetural

## 3. Metas e Restrições da Arquitetura

#### 3.1 - Restrições**

-   O  _software_  deve ser desenvolvido nas tecnologias definidas;
-   O  _software_  deve rodar nos navegadores: Web Firefox e Google Chrome;
-   O ambiente de desenvolvimento do  _software_  deve funcionar tanto em Windows, Linux e MacOS;
-   Para utilizar o  _software_  é necessário ter internet;
-   O escopo do projeto deve ser concluído até o final da disciplina.

#### **3.2 - Metas**

As metas planejadas para a aplicação são:

-   **Portabilidade** – Deve ser possível utilizar a plataforma em qualquer navegador web.
-   **Usabilidade** - O  _software_  deve possuir alta aprendibilidade e inteligibilidade, para que atenda aos requisitos elicitados no formulário criado pelo grupo;
-   **Manutenibilidade** - O código e as documentações realizadas pelo grupo devem estar num nível de qualidade, seguindo os padrões de projeto e bibliografia, onde a sua manutenção seja fácil de ser realizada.

## 4. Visão de Casos de Uso

Para representação dos Casos de Uso do sistema especificado, foi criado um diagrama de Casos de Uso que expões os pontos principais do sistema. 

![Diagrama de Casos de Uso](/img/Casos_de_uso-Easy_Caffee.png)


### Especificação dos Casos de Uso

#### Atores

- **Dono da Cafeteria (Admin do sistema):** São os donos e/ou funcionários da cafeteria. Eles são responsáveis por manter os produtos, bem como suas informações e também gerenciar o glossário.

- **Cliente da Cafeteria:** São os usuários do sistema, que o utilizarão com o objetivo de realizar compras dos produtos da cafeteria. 

#### Casos de Uso

- **Realizar Cadastro:** Essa ação é realizada pelo cliente da cafeteria, para manter um cadastro no sistema, o que possibilita as compras de produtos e o acompanhamento de informações sobre as compras etc. 
*Ator(es) Relacionado(s):* Cliente da Cafeteria.       
*Requisitos Relacionados:* [RF01](../entrega01/requisitos.md)

- **Fazer Login:** Essa ação é realizada tanto pelo cliente quanto pelo dono da cafeteria, para ter acesso a algumas funcionalidades do sistema.
*Ator(es) Relacionado(s):* Dono da Cafeteria e Cliente da Cafeteria.         
*Requisitos Relacionados:* [RF01, RF02](../entrega01/requisitos.md).
  
- **Gerenciar Produtos:** A ação de gerenciar produtos é feita pelo dono da cafeteria, e isso engloba atividades como cadastrar, editar e excluir produtos. Bem como colocar algum produto em promoção. 
*Ator(es) Relacionado(s):* Dono da Cafeteria          
*Requisitos Relacionados:* [RF03, RF04, RF05, RF06, RF07, RF30](../entrega01/requisitos.md).

- **Gerenciar Glossário:** A ação de gerenciar produtos é feita pelo dono da cafeteria, e inclui atividades como adicionar, editar e excluir informações do glossário.
*Ator(es) Relacionado(s):* Dono da Cafeteria         
*Requisitos Relacionados:* [RF26, RF27, RF28, RF29](../entrega01/requisitos.md).
 
- **Gerenciar Carrinho de Compras:** Essa ação é realizada pelo cliente da cafeteria, e inclui atividades como adicionar ou excluir produtos do carrinho, e editar as quantidades dos produtos no carrinho.
*Ator(es) Relacionado(s):* Cliente da Cafeteria.         
*Requisitos Relacionados:* [RF14, RF15](../entrega01/requisitos.md).

- **Realizar Compras:** Essa ação é realizada pelo cliente, após adicionar um ou mais produtos no carrinho, aonde ele efetua a compra, realiza o pagamento e pode acompanhar o pedido até esse chegar em sua casa.
*Ator(es) Relacionado(s):* Cliente da Cafeteria.         
*Requisitos Relacionados:* [RF16, RF17, RF18](../entrega01/requisitos.md).

## 5. Visão Lógica

A visão lógica descreve como o sistema é estruturado, em termos de unidade e implementação. Mostra como está a organização conceitual do sistema em termos de camadas, pacotes, classes e interfaces. O relacionamento entre os elementos mostra as dependências, as realizações de interface, os relacionamento parte-todo e assim por diante.

### 5.1 Diagrama de Classes

O Diagrama de Classes representa como que as classes serão realmente programadas, os principais objetos ou as interações entre classes e objetos. O diagrama completo pode ser encontrado na parte de [Diagrama de Classes](../entrega2/diagramas_uml/diagrama_de_classe.md) na wiki do projeto.

A versão apresentada é a mais recente do projeto.

![alt text](../img/diagrama_classe/Diagrma_de_Classev3.png)

Autores: [Itallo Gravina](https://github.com/itallogravina), [Danilo Domingo](https://github.com/danilow200), [Gabrielle Ribeiro](https://github.com/Gabrielle-Ribeiro), [Gustavo Afonso](https://github.com/GustavoAPS) e [Rafael Ribeiro](https://github.com/rafaelflarrn)

### 5.2 Diagrama de Pacotes

O Diagrama de Pacotes, é um diagrama estático que possibilita a organização mais adequada do sistema representando uma visão em Pacotes. O diagrama completo pode ser encontrado na parte de [Diagrama de Pacotes](../entrega2/diagramas_uml/diagrama_de_pacotes.md) na wiki do projeto.

A versão apresentada é a mais recente do projeto.

![alt text](../img/uml/Diagrama_de_Pacotes.png)

Autor: [Danilo Domingo](https://github.com/danilow200)

### 5.3 Diagrama de Comunicação

O Diagrama de Comunicação é um diagrama que mostra interações entre objetos e/ou partes(representadas pelas lifelines) usando mensagens sequenciadas em um arranjo de forma livre. O diagrama completo pode ser encontrado na parte de [Diagrama de Comunicação](../entrega2/diagramas_uml/diagrama_de_comunicacao.md) na wiki do projeto.

A versão apresentada é a mais recente do projeto.

#### Diagrama de Comunicação Cliente

![alt text](../../img/uml/Diagrama_de_Comunicacao.png)

Autor: [Rafael Ribeiro](https://github.com/rafaelflarrn)
#### Diagrama de Comunicação Funcionario

![alt text](../../img/uml/Diagrama_de_Comunicacao(Funcionario).png)

Autor: [Rafael Ribeiro](https://github.com/rafaelflarrn)
## 6. Visão de Processos
  Descreve como o sistema de tempo-de-execução é estruturado na forma de um conjunto de elementos que têm interações e comportamento de tempo-de-execução. A estrutura de tempo-de-execução normalmente tem pouca semelhança com a estrutura de código. Consiste de redes de comutação rápida de objetos de comunicação.

## 7. Visão de Deploy


## 8. Visão de Implementação
Descreve como os artefatos de desenvolvimento estão organizados no sistema de arquivos. Os elementos são arquivos e diretórios (quaisquer itens de configuração). Isto inclui os artefatos de desenvolvimento e os artefatos de implantação. Esta visão é opcional quando do uso das Visões 4+1.

## 9. Tamanho e Desempenho

### 9.1 Visão Geral

Discrição do desempenho e das características do software que impactam na arquitetura de software.

### 9.2 Requisitos Mínimos

- É necessário possuir conexão com a internet;
- Navegador com suporte a HTML 5, CSS e JavaScript;
- Para desenvolvimento de possuir: Windows, Linux ou MacOS;

## 10. Qualidade

Qualidade de software tem como objetivo atingir requisitos especificados durante a elaboração do projeto, e as necessidades ou expectativas de usuários e clientes, esntando relacionado diretamente com: escalabilidade, manutebilidade, confiabilidade, usuabilidade e assim por diante.

### 9.1 NFR

O NFR é utilziado para rastrear os requisistos não funcionais. Seu objetivo é ajudar desenvolvedores na implementação de soluções personalizadas, levando em consideração as características do domínio e do sistema em questão, para o projeto foi criado 5 NFRs, que pode ser incontrado na parte de [Requisistos Não Funcionais](../entrega1/requisitos_nao_funcionais.md) da documentação do projeto, para que o documento não fiquei poluido será apresentando apenas o NFR de desempenho.

#### Desempenho

![alt text](../entrega1/img/NFR/NFR_desempenho.png)

Autores: [Iago Theóphilo](https://github.com/IagoTheophilo), [Itallo Gravina](https://github.com/itallogravina) e [Maicon Mares](https://github.com/MaiconMares)

#### Desempenho(propagação)

![alt text](../entrega1/img/NFR/diagrama_desempenho(propagacao).jpg)

Autores: [Iago Theóphilo](https://github.com/IagoTheophilo), [Itallo Gravina](https://github.com/itallogravina) e [Maicon Mares](https://github.com/MaiconMares)

## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|02/05/2021|1.0|Adiciona estrutura inicial do Documento de Arquitetura de Software|[Danilo Domingo](https://github.com/danilow200)|
|02/05/2021|1.1|Adiciona tamanho e desempenho|[Danilo Domingo](https://github.com/danilow200)|
|02/05/2021|1.2|Adiciona qualidade|[Danilo Domingo](https://github.com/danilow200)|
|02/05/2021|1.3|Adiciona Visão Lógica|[Danilo Domingo](https://github.com/danilow200)|
|02/05/2021|1.3|Adiciona Visão Lógica Metas e Restrições da Arquitetura|[itallo gravina](https://github.com/itallogravina)|
|03/05/2021|1.4|Adiciona Casos de Uso|[Gabrielle Ribeiro](https://github.com/Gabrielle-Ribeiro), [Gustavo Afonso](https://github.com/GustavoAPS)|