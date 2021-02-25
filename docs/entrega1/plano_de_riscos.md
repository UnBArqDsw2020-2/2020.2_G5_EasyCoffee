# Plano de Gerenciamento de Riscos

## Introdução

<p align="justify">Esse documento tem como objetivo planejar como o gerenciamento dos riscos será executado, monitorado e controlado. Risco pode ser definido como “evento ou condição incerta que, se ocorrer, terá um efeito positivo ou negativo sobre pelo menos um objetivo do projeto” (PMBOK, 2004). Logo, temos riscos negativos (afetam objetivos) e riscos positivos (oportunidade que se ocorrer beneficiará o projeto). Para gerenciamento dos riscos (identificar, manter e controlar) as seguintes etapas fazem-se necessárias: identificação dos riscos, análise qualitativa, análise quantitativa, respostas aos riscos e monitoramento.

## Estrutura Analítica de Riscos (EAR)
<p align="justify">Por meio do diagrama a seguir podemos definir os riscos que podem afetar o projeto em quatro categorias gerais: Técnico, Externo, Organizacional e Gerenciamento de projeto.</p>

<p align="center">
    <img src="https://github.com/UnBArqDsw2020-2/2020.2_G5_EasyCoffee/blob/master/docs/entrega1/img/plano_de_riscos/easy_coffee_EAR.png?raw=true"/>
    <br>
    <i>Estrutura Analítica de Riscos - EasyCoffee</i>
</p>

### Técnico
<p align="justify">Requisitos: Esses riscos envolvem os requisitos, surgem normalmente devido a tarefas mal realizadas, como Elicitação e Análise e Negociação.
Tecnologia: Relacionam-se às tecnologias utilizadas no projeto e também do relacionamento dos membros da equipe com aquelas.
Infraestrutura: É o conjunto de todos os componentes e serviços que fornecem a base para sustentar todo o sistema de informação. Sendo um dos pilares de qualquer projeto de software, pode afetá-lo por inteiro.
</p>

### Externo
<p align="justify">Mercado: Obsolescência da aplicação ou baixa adesão devido a outras soluções. 
Ambiente: Os riscos aqui relacionam-se com o ambiente externo, não o ambiente de desenvolvimento e suas dependências. No contexto atual de Pandemia, o trabalho está sendo executado de maneira remota, cada membro em sua casa. A falta de acesso à Internet e morar em um ambiente com outras pessoas que também possuem afazeres podem diminuir a produtividade da equipe e afetar diretamente o desenvolvimento.
</p>

### Organizacional
<p align="justify">Dependências do projeto: Referem-se às dependências externas, projetos externos e fornecedores de recursos.
Recursos humanos: Compreende qualquer risco que possa afetar os recursos humanos (membros da equipe), como adquirir o vírus SARS-CoV-2, como também problemas na comunicação entre os membros e comprometimento.
Priorização: Aqui os riscos estão ligados a erros no planejamento, como por exemplo priorização de tarefas menos importantes e/ou que possuem dependências de tarefas que foram definidas para serem executadas posteriormente.
</p>

### Gerenciamento de projeto
<p align="justify">Planejamento: Estão relacionados a riscos no planejamento do projeto, como escopo impraticável para o tempo disponível.
Estimativa: Envolve erros de estimativa, como tamanho do projeto, esforço e custo.
Controle: Esses riscos envolvem riscos que foram identificados, porém nenhuma ação foi executada para contorná-los.
Comunicação: Os riscos desta subcategoria podem surgir em consequência a erros na comunicação com stakeholders, o que pode levar a retrabalho e até entrega do projeto errado devido à má comunicação.
</p>

## Análises qualitativa e quantitativa
<p align="justify">Nesta fase, definimos métricas de impacto e probabilidade para os riscos e posteriormente as analisamos de forma numérica e atribuímos as métricas resultantes aos riscos. Essas métricas serão construídas através de uma matriz de probabilidade e impacto em que é descrito a probabilidade de um risco ocorrer e seu impacto em um objetivo. 
</p>

### Probabilidade
<table>
    <tr>
        <th>Probabilidade(P)</th>
        <th>Peso</th>
    </tr>
    <tr>
        <td>Muito Baixa</td>
        <td>1</td>
    </tr>
    <tr>
        <td>Baixa</td>
        <td>2</td>
    </tr>
    <tr>
        <td>Moderada</td>
        <td>3</td>
    </tr>
    <tr>
        <td>Alta</td>
        <td>4</td>
    </tr>
    <tr>
        <td>Muito Alta</td>
        <td>5</td>
    </tr>
</table>

### Impacto
<table>
    <tr>
        <th>Impacto (I)</th>
        <th>Descrição</th>
        <th>Peso</th>
    </tr>
    <tr>
        <td>Muito Baixa</td>
        <td>
            Quase imperceptível ao projeto
        </td>
        <td>1</td>
    </tr>
    <tr>
        <td>Baixa</td>
        <td>
            Impacto tem pouca influência no projeto
        </td>
        <td>2</td>
    </tr>
    <tr>
        <td>Moderada</td>
        <td>
            Impacto considerável, mas recuperável
        </td>
        <td>3</td>
    </tr>
    <tr>
        <td>Alta</td>
        <td>
            Tem grande impacto no projeto
        </td>
        <td>4</td>
    </tr>
    <tr>
        <td>Muito Alta</td>
        <td>
            Detém o prosseguimento do projeto
        </td>
        <td>5</td>
    </tr>
</table>

### Matriz de Probabilidade e Impacto

<table>
    <tr>
        <th>P/I</th>
        <th>Muito Baixo</th>
        <th>Baixo</th>
        <th>Moderado</th>
        <th>Alto</th>
        <th>Muito Alto</th>
    </tr>
    <tr>
        <th>Muito Baixa</th>
        <td>1</td>
        <td>2</td>
        <td>3</td>
        <td>4</td>
        <td>5</td>
    </tr>
    <tr>
        <th>Baixa</th>
        <td>2</td>
        <td>4</td>
        <td>6</td>
        <td>8</td>
        <td>10</td>
    </tr>
    <tr>
        <th>Moderada</th>
        <td>3</td>
        <td>6</td>
        <td>9</td>
        <td>12</td>
        <td>15</td>
    </tr>
    <tr>
        <th>Alta</th>
        <td>4</td>
        <td>8</td>
        <td>12</td>
        <td>16</td>
        <td>20</td>
    </tr>
    <tr>
        <th>Muito Alta</th>
        <td>5</td>
        <td>10</td>
        <td>15</td>
        <td>20</td>
        <td>25</td>
    </tr>
</table>
<br>

### Prioridade
<p align="justify"> Como resultado da matriz acima obtemos a prioridade de cada risco.</p>

<table>
    <tr>
        <th>Prioridade</th>
        <th>Intervalo</th>
    </tr>
    <tr>
        <td>Baixa</td>
        <td>1-5</td>
    </tr>
    <tr>
        <td>Média</td>
        <td>6-15</td>
    </tr>
    <tr>
        <td>Alta</td>
        <td>16-25</td>
    </tr>
</table>

### Matrizes de Impacto
#### Riscos técnicos

<table>
    <tr>
        <th>Risco</th>
        <th>Impacto</th>
        <th>Probabilidade</th>
        <th>Prevenção</th>
        <th>Resposta</th>
        <th>Prioridade</th>
    </tr>
    <tr>
        <td>
            Levantamento incompleto/    errôneo dos requisitos
        </td>
        <td>
            Muito Alto
        </td>
        <td>
            Baixa
        </td>
        <td>
            Participação de todos no levantamento, uso de diferentes técnicas e estudo de domínios similares
        </td>
        <td>
            Revisar e refazer os requisitos
        </td>
        <td>10</td>
    </tr>
    <tr>
        <td>
            Inexperiência/desconhecimento das tecnologias 
        </td>
        <td>
            Alto
        </td>
        <td>
            Baixa
        </td>
        <td>Realização de treinamentos coletivos e estudo individual</td>
        <td>Pareamento com membros mais experientes</td>
        <td>8</td>
    </tr>
    <tr>
        <td>Atrasos no projeto</td>
        <td>Alto</td>
        <td>Média</td>
        <td>Medir o nível de conhecimento de cada membro e equilibrar as tarefas delegadas</td>
        <td>Replanejar e redistribuir as tarefas</td>
        <td>12</td>
    </tr>
    <tr>
        <td>Incompatibilidade entre softwares e dependências dos membros</td>
        <td>Baixo</td>
        <td>Baixa</td>
        <td>Utilizar soluções de conteinerização como Docker    </td>
        <td>Rever caso específico do(s) membro(s) afetado(s)</td>
        <td>4</td>
    </tr>
</table>

#### Riscos Externos

<table>
    <tr>
        <th>Risco</th>
        <th>Impacto</th>
        <th>Probabilidade</th>
        <th>Prevenção</th>
        <th>Resposta</th>
        <th>Prioridade</th>
    </tr>
    <tr>
        <td>Baixa utilização da aplicação</td>
        <td>Alto</td>
        <td>Alta</td>
        <td>Validação com o público alvo</td>
        <td>Análise de soluções semelhantes com grande adesão e adaptação da nossa solução</td>
        <td>16</td>
    </tr>
    <tr>
        <td>Trabalhar em ambiente doméstico com muitos ruídos e outras pessoas executando outras tarefas</td>
        <td>Médio</td>
        <td>Alta</td>
        <td>Cada membro fixar seu melhor horário para trabalhar</td>
        <td>Pedir compreensão dos demais no recinto e usar soluções de cancelamento de ruído</td>
        <td>12</td>
    </tr>
</table>

#### Riscos Organizacionais

<table>
    <tr>
        <th>Risco</th>
        <th>Impacto</th>
        <th>Probabilidade</th>
        <th>Prevenção</th>
        <th>Resposta</th>
        <th>Prioridade</th>
    </tr>
    <tr>
        <td>Recursos externos necessários ao projeto serem pagos ou o suporte ser cancelado no meio do projeto</td>
        <td>Alto</td>
        <td>Baixa</td>
        <td>Conhecer diversas opções semelhantes</td>
        <td>Readaptar a solução para utilizar recursos de outros fornecedores</td>
        <td>8</td>
    </tr>
    <tr>
        <td>Falta de motivação e/ou comprometimento dos membros e baixas na equipe</td>
        <td>Alto</td>
        <td>Média</td>
        <td>Manter a harmonia entre a equipe e estimular o relacionamento entre os membros</td>
        <td>Reorganização das atividades da equipe, desenvolver atividades que estimulem o relacionamento e cobrança mútua entre os membros</td>
        <td>12</td>
    </tr>
    <tr>
        <td>Problemas de comunicação/conflitos entre os membros</td>
        <td>Muito Alto</td>
        <td>Média</td>
        <td>Utilizar meios de comunicação de fácil utilização e manter a harmonia entre os membros</td>
        <td>Identificar conflitos, reorganizar pareamentos e mudar canais de comunicação</td>
        <td>15</td>
    </tr>
    <tr>
        <td>Priorização errada das tarefas</td>
        <td>Muito Alto</td>
        <td>Baixa</td>
        <td>Todos participarem da divisão das tarefas e revisarem</td>
        <td>Replanejar as tarefas e redistribuí-las</td>
        <td>10</td>
    </tr>
</table>

#### Riscos de Gerenciamento de Projeto

<table>
    <tr>
        <th>Risco</th>
        <th>Impacto</th>
        <th>Probabilidade</th>
        <th>Prevenção</th>
        <th>Resposta</th>
        <th>Prioridade</th>
    </tr>
    <tr>
        <td>Mal definição do escopo</td>
        <td>Muito Alto</td>
        <td>Baixa</td>
        <td>Analisar projetos semelhantes já realizados e todos participarem da definição do escopo</td>
        <td>Redefinir o escopo</td>
        <td>10</td>
    </tr>
    <tr>
        <td>Cronograma irreal para o contexto</td>
        <td>Muito Alto</td>
        <td>Baixa</td>
        <td>Mensurar com a participação de todos o tempo necessário para realizar cada atividade</td>
        <td>Redefinir o cronograma</td>
        <td>10</td>
    </tr>
    <tr>
        <td>Problemas de comunicação com stakeholders</td>
        <td>Muito Alto</td>
        <td>Média</td>
        <td>Se comunicar com clareza, dando exemplos quando necessário da informação que se deseja passar e pedir feedback constante</td>
        <td>Identificar erros/ambiguidades e mudar as técnicas de comunicação</td>
        <td>15</td>
    </tr>
</table>

## Referências
<p align="justify">[1] Project Management Institute. (2017). A guide to the Project Management Body of Knowledge (PMBOK guide) (6th ed.). Project Management Institute.
</p>

<p align="justify">[2] Isotani e Rocha, Gestão de Riscos em Projetos de Software. Butantã - São Paulo. Disponível em: <https://edisciplinas.usp.br/pluginfile.php/3385127/mod_resource/content/1/Aula10-GerenciaProjeto-Riscos.pdf>. Acesso em: 16 de fevereiro de 2021.</p>

<p align="justify">[3] Gerenciamento de riscos em projetos: o que é e como fazer. Disponível em: <https://artia.com/blog/gerenciamento-de-riscos-em-projetos-o-que-e-e-como-fazer/>. Acesso em: 16 de fevereiro de 2021.</p>

<p align="justify">[4] Plano de Gerenciamento de Riscos. Disponível em: <https://2019-2-arquitetura-desenho.github.io/wiki/dinamica_seminario_II/controle_riscos/>. Acesso em: 16 de fevereiro de 2021.</p>

<p align="justify">[5] Plano de Riscos. Disponível em: <https://github.com/DesenhoMaster2017/SpaceShooter/wiki/Plano-de-Riscos>. Acesso em: 16 de fevereiro de 2021.</p>


## Versionamento

<table>
<tr>
    <th>Data</th>
    <th>Descrição</th>
    <th>Versão</th>
    <th>Autor(es)</th>
</tr>
<tr>
    <td>16/02/2021</td>
    <td>
Plano de Riscos inicial

</td>
    <td>
1.0

</td>
    <td>Maicon Mares</td>
</tr>
</table>
