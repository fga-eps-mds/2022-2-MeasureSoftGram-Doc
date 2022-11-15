# Análise de Risco

## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|13/11/2022|1.0|Criação do documento| João Victor Valadão, Lucas Melo, João Pedro Moura, Ítalo Fernandes |
|15/11/2022|1.1|Adição da estrutura anaĺitica de risco| João Victor Valadão, Lucas Melo, João Pedro Moura, Ítalo Fernandes |


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


## Refêrencia

> [1] TERLIZZI, Marco Alexandre; BIANCOLINO, César Augusto. <b>Estrutura Analítica de Riscos em Projetos de Desenvolvimento de Software no Setor Bancário: Um Estudo Exploratório</b>. Revista Gestão & Tecnologia, [S. l.], p. 51-78, 1 maio 2014. Disponível em: [revistagt.fpl.emnuvens.com.br/get/article/viewFile/628/534](revistagt.fpl.emnuvens.com.br/get/article/viewFile/628/534). Acesso em: 13 de nov. de 2022.

> [2] <b>Gerenciando os riscos do projeto com a matriz de probabilidade e impacto</b>. Disponível em: [https://glicfas.com.br/estrutura-analitica-de-riscos-2/](https://glicfas.com.br/estrutura-analitica-de-riscos-2/). Acesso em: 13 de nov. de 2022.

> [3] VARGAS, Ricardo; <b>Elaborando a Estrutura Analítica do Projeto (EAP/WBS) - Videocast</b>. Disponível em: [https://ricardo-vargas.com/pt/videos/videocast-preparing-the-work-breakdown-structure-wbs/](https://ricardo-vargas.com/pt/videos/videocast-preparing-the-work-breakdown-structure-wbs/). Acesso em: 3 jul. 2022.
