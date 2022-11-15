# Análise de Risco

## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|13/11/2022|1.0|Criação do documento| João Victor Valadão, Lucas Melo, João Pedro Moura, Ítalo Fernandes |
|15/11/2022|1.1|Adição da estrutura anaĺitica de risco| João Victor Valadão, Lucas Melo, João Pedro Moura, Ítalo Fernandes |
|15/11/2022|1.2|Adição da planilha de riscos| João Victor Valadão, Lucas Melo, João Pedro Moura, Ítalo Fernandes |
|15/11/2022|1.3|Adição tabelas de burndown de riscos| João Victor Valadão, Lucas Melo, João Pedro Moura, Ítalo Fernandes |


## Estrutura Analítica de Riscos

<p align="justify" style="text-indent: 20px">O planejamento de riscos consiste em uma das partes mais importantes do planejamento de um projeto, uma vez que definidos quais são os riscos que podem ocorrer, é possível definir estratégias para minimizar os impactos que esses riscos podem causar no projeto. Para isso, é necessário identificar os riscos que podem ocorrer, analisar a probabilidade de cada um deles ocorrer e seu respectivo impacto ao desenvolvimento da aplicação. A partir disso, é possível definir estratégias para minimizar os impactos que esses riscos podem causar no projeto [<a href=./#referencia>1</a>].</p>

<p align="justify" style="text-indent: 20px">Assim, a estrutura analítica de riscos é uma ferramenta que permite a identificação, análise e priorização dos riscos que podem ocorrer durante o desenvolvimento do projeto. Com o objetivo de facilitar a identificação dos riscos, a estrutura analítica de riscos é dividida em categorias: riscos organizacionais, riscos de gerenciamento do projeto, riscos técnicos e riscos externo (EAR)[<a href=./#referencia>2</a>], agrupamento e organização. Essa categorização, pode ser observada de uma forma mais visual com a diagramação a seguir:</p>

<!-- https://miro.com/app/board/uXjVOo14XqA=/ -->
<iframe src="https://miro.com/app/live-embed/uXjVOo14XqA=/?moveToViewport=-641,-238,1276,1606&embedId=734205859227" scrolling="no" allowfullscreen style="width: 100%; height: 500px" frameborder="0"></iframe>

**Externo**:

- Faculdade: Riscos relacionados à outras disciplinas que acontecem durante o projeto.
- Saúde: Riscos relacionados à saúde dos integrantes e clientes do projeto. Onde em casos extremos pode levar a volta do sistema de ensino à distância.
- Profissional: Riscos relacionados às vidas profissionais dos integrantes.
- Cliente: Riscos associados à indisponibilidades dos clientes.

**Organizacional**:

- Priorização: Riscos associados à possíveis priorizações equivocadas dos requisitos, de acordo com a perspectiva do cliente.
- Financiamento: Riscos inerentes aos custos do projeto com a existência de possíveis financiamentos monetários no projeto.
- Habilidades individuais: Riscos relacionados com às capacidades e habilidades de cada integrante.

**Técnico**:

- Dependências de projeto: Riscos relacionados com dependências externas utilizadas no projeto.
- Tecnologia: Riscos associados com as tecnologias utilizadas.
- Infraestrutura: Riscos relacionandos com a infraestrutura do projeto.
- Arquitetura: Riscos relacionados com a arquitetura utilizada no projeto.
- Qualidade: Riscos associados às características de qualidade do produto.

**Gerenciamento do projeto**:

- Pessoas: Riscos relacionados com a gerência das pessoas integrantes do projeto.
- Estimativas: Riscos relacionados com a definição e alterações das estimativas definidas para o projeto.
- Planejamento: Riscos relacionados ao planejamento do projeto.
- Execução: Riscos associados com a execução do projeto.
- Comunicação: Riscos associados com a comunicação entre membros e entre clientes.

## Análise Quantitativa

### Probabilidade
**Probabilidade** | **Intervalo** | **Peso**
:---------------: | :-----------: | :------:
**Muito Alta**    |   81 ~ 100    |    5
**Alta**          |   61 ~ 80     |    4
**Média**         |   41 ~ 60     |    3
**Baixa**         |   21 ~ 40     |    2
**Muito Baixa**   |   0 ~ 20      |    1

### Impacto
**Impacto**       |                     **Descrição**                      | **Peso**
:---------------: | :----------------------------------------------------: | :------:
**Muito Alto**    | O impacto inviabiliza o projeto                        |    5
**Alto**          | Há grande impacto no desenvolvimento do projeto        |    4
**Médio**         | Possui certo impacto porém é facilmente recuperado     |    3
**Baixo**         | Pouco impacto no desenvolvimento do projeto            |    2
**Muito Baixo**   | Impacto pouco expressivo no desenvolvimento do projeto |    1

### Prioridade (Probabilidade x Impacto)

<p align="justify" style="text-indent: 20px">Multiplicando-se a probabilidade de um risco acontecer pelo seu impacto no projeto, é possível se calcular a prioridade do risco. Esses valores determinam a urgência por medidas de mitigação, atenuação ou resolução desses riscos. O quadro abaixo identifica essa matriz elaborada:</p>

**Probabilidade x Impacto** | **Muito Baixo** | **Baixo** | **Médio**  | **Alto** | **Muito Alto**
:-----------------------: | :-------------: | :-------: |:----------:|:--------:|:------------: 
**Muito Alta**            |        5        |    10     |      15    |    20    |      25
**Alta**                  |        4        |    8      |      12    |    16    |      20
**Média**                 |        3        |    6      |      9     |    12    |      15
**Baixa**                 |        2        |    4      |      6     |    8     |      10
**Muito Baixa**           |        1        |    2      |      3     |    4     |      5

## Planilha de Riscos

<p align="justify" style="text-indent: 20px">Após o entendimento das fontes de riscos encontradas no projeto (Organizacional, Externo, Gerênciamento de projeto e Técnico), foram confeccionadas diversas tabelas identificando as suas probabilidades, impactos, prevenções e respostas. Esse detalhamento, assistiu à todas as sprints permitindo a equipe gerênciar e melhor se organizar durante a execução do projeto.</p>

**Externo**:

|ID|Risco|Probabilidade|Impacto|Prevenção|Resposta|
|:-:|:-:|:-:|:-:|:-:|:-:|
|R1|Indisponibilidade do cliente no decorrer do projeto|Médio|Alto|Organizar, comunicar e definir horários com os clientes|Repriorizar/Alterar para problemas que não envolvem o cliente|
|R2|Indisponibilidades dos integrantes por motivos profissionais|Alto|Médio|Planejamento e divisão de tarefas|Redistribuição de tarefas entre a equipe|
|R3|Indisponibilidades dos integrantes por motivos de saúde|Médio|Baixo|Sempre estar atento às medidas de saúde|Redistribuição de tarefas entre a equipe|
|R4|Indisponibilidades dos integrantes por demandas da faculdade|Médio|Médio|-|Redistribuição de tarefas entre a equipe|

**Organizacional**:

|ID|Risco|Probabilidade|Impacto|Prevenção|Resposta|
|:-:|:-:|:-:|:-:|:-:|:-:|
|R5|Realização de pareamentos de forma ineficiente|Baixo|Médio|Entendimento dos conhecimentos e habilidades da equipe|Reparear ou transformar pareamento em um grupo com mais integrantes|
|R6|Priorização equivocada das tarefas|Médio|Muito Alto|Entendimento do produto, avaliações com os clientes, comunicação entre a equipe|Repriorizar e se for necessário levantar novos requisitos|
|R7|Familiaridade com a tecnologia|Médio|Médio|Avaliação do quadro de conhecimento da equipe|Realização de treinamentos e divulgação do conhecimento|
|R8|Financiamento do projeto|Baixo|Baixo|-|Avaliação dos requisitos, apresentação do projeto, comunicação com os clientes|

**Técnico**:

|ID|Risco|Probabilidade|Impacto|Prevenção|Resposta|
|:-:|:-:|:-:|:-:|:-:|:-:|
|R9|Utilização de bibliotecas desatualizadas/comprometidas|Muito Baixo|Alto|Avaliação antes do uso/escolha da biblioteca|Implementação própria ou mudança de biblioteca|
|R10|Utilização de tecnologias que não atendem às demandas|Muito Baixo|Médio|Avaliação prévia da tecnologia e das suas funcionalidades|Refatorações de código|
|R11|Infraestrutura definida não atende o projeto|Alto|Muito Alto|Avaliação dos custos e capacidades da infraestrutura escolhida|Alteração da infraestrutura do projeto|
|R12|Arquitetura definida não atende o projeto|Baixo|Alto|Análise e avaliação da arquitetura utilizada ou que se deseja utilizar|Alteração da arquitetura definida envolvendo refatorações de código|
|R13|Qualidade de código|Médio|Alto|Análise estática de código, avaliação de acordo com os padrões esperados de qualidade|Refatorações de código|

**Gerênciamento de projeto**:

|ID|Risco|Probabilidade|Impacto|Prevenção|Resposta|
|:-:|:-:|:-:|:-:|:-:|:-:|
|R14|Perda de reuniões da equipe|Baixo|Médio|Análise do quadro de disponiblidades do grupo|Realização de reuniões rápidas, gravação das reuniões|
|R15|Saida de membros da equipe|Baixo|Médio|Sempre ajudar os membros com mais dificuldades, avaliações de stress mental e saude da equipe|Realocação dos membros nas atividades|
|R16|Subestimativas ou Superestimativas|Alto|Médio|Avaliação das estimativas com a equipe, conhecimento do projeto|Reavaliação das estimativas propostas|
|R17|Falta de planejamento|Baixo|Alto|Planejamentos com antecedência sempre levando em conta a capacidade e disponibilidade dos membros|Replanejamento e possível realocação de membros nas atividades|
|R18|Atrasos nas execuções das atividades|Médio|Alto|Entendimento dos cronogramas e das capacidades dos integrantes|Reavaliação do cronograma e das tarefas que são esperadas para as entregas|
|R19|Falta de comunicação entre a equipe e entre os clientes|Baixo|Alto|Manter canal de comunicação entre a equipe e entre o cliente sempre bem ativo|Propor atividades para interação do grupo|

## Burndown de Riscos

<p align="justify" style="text-indent: 20px">Para melhorar a visualização do desenvolvimento dos riscos durante a execução do projeto, foram utilizados quadros de <i>burndown</i> para cada agrupamento de risco. Nesses gráficos, portanto, é possível notar e comparar a evolução dos riscos de acordo com as <i>sprints</i> do projeto. O quadro pode ser melhor visualizado <a href="https://docs.google.com/spreadsheets/d/e/2PACX-1vTyXZTCcepxg9H42ZtYSulpsa6D2KLQi8k-SY9mDJr1UC1no4UKsTk4-NL36UEV3TOdeGcKDOXS_-MX/pubhtml?widget=true&amp;headers=false">aqui</a>.</p>

<iframe style="width: 100%; height: 500px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTyXZTCcepxg9H42ZtYSulpsa6D2KLQi8k-SY9mDJr1UC1no4UKsTk4-NL36UEV3TOdeGcKDOXS_-MX/pubhtml?widget=true&amp;headers=false"></iframe>

## Refêrencia

> [1] TERLIZZI, Marco Alexandre; BIANCOLINO, César Augusto. <b>Estrutura Analítica de Riscos em Projetos de Desenvolvimento de Software no Setor Bancário: Um Estudo Exploratório</b>. Revista Gestão & Tecnologia, [S. l.], p. 51-78, 1 maio 2014. Disponível em: [revistagt.fpl.emnuvens.com.br/get/article/viewFile/628/534](revistagt.fpl.emnuvens.com.br/get/article/viewFile/628/534). Acesso em: 13 de nov. de 2022.

> [2] <b>Gerenciando os riscos do projeto com a matriz de probabilidade e impacto</b>. Disponível em: [https://glicfas.com.br/estrutura-analitica-de-riscos-2/](https://glicfas.com.br/estrutura-analitica-de-riscos-2/). Acesso em: 13 de nov. de 2022.

> [3] VARGAS, Ricardo; <b>Elaborando a Estrutura Analítica do Projeto (EAP/WBS) - Videocast</b>. Disponível em: [https://ricardo-vargas.com/pt/videos/videocast-preparing-the-work-breakdown-structure-wbs/](https://ricardo-vargas.com/pt/videos/videocast-preparing-the-work-breakdown-structure-wbs/). Acesso em: 3 jul. 2022.
