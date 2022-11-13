# Análise de Risco

## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|13/11/2022|1.0|Criação do documento| João Victor Valadão, Lucas Melo, João Pedro Moura, Ítalo Fernandes |


## Estrutura Analítica de Riscos

<p align="justify" style="text-indent: 20px">O planejamento de riscos consiste em uma das partes mais importantes do planejamento de um projeto, uma vez que definidos quais são os riscos que podem ocorrer, é possível definir estratégias para minimizar os impactos que esses riscos podem causar no projeto. Para isso, é necessário identificar os riscos que podem ocorrer, analisar a probabilidade de cada um deles ocorrer e seu respectivo impacto ao desenvolvimento da aplicação. A partir disso, é possível definir estratégias para minimizar os impactos que esses riscos podem causar no projeto [<a href=./#referencia>1</a>].</p>

<p align="justify" style="text-indent: 20px">Assim, a estrutura analítica de riscos  é uma ferramenta que permite a identificação, análise e priorização dos riscos que podem ocorrer durante o desenvolvimento do projeto. Com o objetivo de facilitar a identificação dos riscos, a estrutura analítica de riscos é dividida em categorias: riscos organizacionais, riscos de gerenciamento do projeto, riscos técnicos e riscos externo (EAR)[<a href=./#referencia>2</a>], agrupamento e organizaçãoEssa categorização, pode ser observada de uma forma mais visual com a diagramação a seguir:s.</p>

<!-- adicionar diagrama -->

**Organizacional**:

- Estratégia: Alterações na estratégia afeta diretamente o andamento do projeto, podendo causar uma perda do trabalho já realizado.
- Estrutura: O ambiente onde é realizado o trabalho pode dificultar o desenvolvimento.
- Prioridade: O projeto pode sofrer pausas e cancelamentos devido à mudanças de prioridade, criando atraso geral.

**Gerenciamento do projeto**:

- Mudanças no escopo: Mudanças no escopo do projeto podem ocorrer durante o desenvolvimento, causando impactos no cronograma e no orçamento.
- Planejamento: Planejamento para a evolução da plataforma pode ser realizado de forma equivocada e demandar mais tempo do que o esperado.
- Comunicação: A comunicação entre os membros da equipe pode ser prejudicada por fatores, como a falta de tempo, a falta de interesse ou a falta de conhecimento. Além disso, a comunicação entre a equipe e o cliente também pode não acontecer com a periodicidade desejada.


**Técnico**:

- Requisitos: A equipe pode não conseguir atender a todos os requisitos do cliente, ou não definir corretamente os requisitos do projeto.
- Tecnologia: Os membros da equipe podem não ter conhecimento suficiente acerca das tecnologias utilizadas no projeto.
- Infraestrutura: A equipe pode não conseguir manter a infraestrutura necessária para o desenvolvimento do projeto.
- Arquitetura: Uma vez que a arquitetura do projeto já foi definida, a equipe pode encontrar dificuldades para mante-la diante da implementação de novas funcionalidades.

**Externo**:

<!-- - Faculdade: Outras disciplinas podem influenciar no andamento do projeto.
- Saúde: Integrantes e cliente podem adoecer durante o semestre. Também a o risco de alguem contrair COVID-19 e as aulas tornarsem remotas, por um perído, novamente.
- Cliente/Stakeholder: Cliente pode não está sempre dísponivel.
- Profissional: Vida profissional pode afetar o ritmo e hórarios dos estudantes. -->

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

**Organizacional**:

<!-- | ID  | Risco                                                                             | Probabilidade | Impacto | Prevenção                                               | Plano de ação                                                                                                                                                  |
| --- | --------------------------------------------------------------------------------- | ------------- | ------- | ------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| R1  | Integrantes podem não estar familiarizados com as tecnologias adotadas no projeto | Baixo         | Alto    | Treinar integrantes não familiarizados com a tecnologia | Incentivar treinamentos e tarefas pareadas                                                                                                                     |
| R2  | Realizar pareamentos de forma ineficiente                                         | Médio         | Alto    | Conhecer as habilidades dos membros da equipe           | O time deve realizar pareamentos de uma forma que seja benéfica à equipe. Pelo menos um dos integrantes do pareamento deve ter mais experiência com o problema |
| R3  | Atividades podem ser indicadas de forma equivocada                                | Baixo         | Alto    | Conhecer as habilidades dos membros da equipe           | Criar um quadro de conhecimento para saber a especialidade de cada integrante.                                                                                 | -->

<!-- <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSRNmajBsenuYzDO-3k0z0XIlA1UhBFF1FvxeuyMJThBsKcoyy4jSER5JkrHJf700FhHcpBohI3SO3b/pubhtml?gid=1768542007&amp;single=true&amp;widget=true&amp;headers=false" height="500px"></iframe> -->

**Externo**:

<!-- | ID  | Risco                                                                                               | Probabilidade | Impacto | Prevenção | Plano de ação                                                                         |
| --- | --------------------------------------------------------------------------------------------------- | ------------- | ------- | --------- | ------------------------------------------------------------------------------------- |
| R4  | Indisponibilidade do cliente ao decorrer do projeto                                                 | Alto          | Alto    | -         | Sempre que for possível ou necessário, obter o máximo de informação do cliente assim. |
| R5  | Algum integrante do time pode ficar indisponível                                                    | Alto          | Médio   | -         | Adaptar trabalho do time quando houver necessidade                                    |
| R6  | Demandas na vida profissional e faculdade dos integrantes do time podem afetar andamento do projeto | Alto          | Baixo   | -         | Time deve planejar bem seus horários e disponibilidades                               |

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSRNmajBsenuYzDO-3k0z0XIlA1UhBFF1FvxeuyMJThBsKcoyy4jSER5JkrHJf700FhHcpBohI3SO3b/pubhtml?gid=1194146969&amp;single=true&amp;widget=true&amp;headers=false" height="500px"></iframe> -->

**Gerenciamento de projeto**:

<!-- | ID  | Risco                                                                       | Probabilidade | Impacto | Prevenção                                                                                                 | Plano de ação                                                                                                                         |
| --- | --------------------------------------------------------------------------- | ------------- | ------- | --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| R7  | Alguns integrantes podem acabar perdendo reuniões e informações importantes | Médio         | Baixo   | Identificar horários de disponibilidade de integrantes do grupo                                           | Realizar reuniões rápidas, pelo menos duas vezes por semana, para alinhar time, além disso criar resumo de reuniões longas no Github. |
| R8  | É possível que tarefas sejam estimadas de forma equivocada                  | Baixo         | Alto    | Durante a fase de planejamento, identificar tarefas que sejam muito complexas.                            | Quebrar tarefas muito grandes, ou complexas, em várias pequenas tarefas que tornam o desenvolvimento mais fácil.                      |
| R9  | Muitas tarefas podem acabar indo para a priorizadas e se tornem dívidas     | Alto          | Baixo   | Avaliar as métricas que o Zenhub fornece ao time, dessa forma evitaremos possíveis dívidas técnicas       | Planejar sprints baseado em métricas passadas da equipe.                                                                              |
| R10 | Atrasar execução de uma tarefa                                              | Alto          | Baixo   | Desenvolvedor deve informar a equipe do problema que está ocorrendo para que todos saibam do que se trata | Realizar pareamentos, dessa forma é possível que a tarefa seja entregue de forma mais rápida.                                         |
| R11 | Priorização de tarefas de forma equivocada                                  | Alto          | Baixo   | Validar com o cliente as tarefas que deve ser priorizadas                                             | Realizar planning meetings         
| R12 | Falta de engajamento de membros do grupo                                    | Alto          | Alto    | Realizar reuniões e motivar todos do grupo na realização do projeto                                   | Caso necessário, entregar tarefas "não blocantes" para membros menos engajados |

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSRNmajBsenuYzDO-3k0z0XIlA1UhBFF1FvxeuyMJThBsKcoyy4jSER5JkrHJf700FhHcpBohI3SO3b/pubhtml?gid=993723594&amp;single=true&amp;widget=true&amp;headers=false" height="550px"></iframe> -->

**Tecnico**:

<!-- | ID  | Risco                                                                                        | Probabilidade | Impacto    | Prevenção                                                 | Plano de ação                                                                              |
| --- | -------------------------------------------------------------------------------------------- | ------------- | ---------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| R13 | Arquitetura definida previamente pode não atender requisitos para mutabilidade do produto    | Alto          | Muito Alto | Analisar documento arquitetural e implementação no código | Alterar arquitetura para atender novos requisitos e, se necessário, replanejar arquitetura |
| R14 | Infraestrutura definida previamente deverá ser alterada por não atender requisitos           | Baixo         | Muito Alto | Entender bem sobre a infra estrutura que será utilizada   | Alterar infraestrutura                                                                     |
| R15 | Qualidade do código já escrito pode estar ruim (Code smell, alto acoplamento e baixa coesão) | Alto          | Alto       | Analisar código e entender sua lógica                     | Refatorar o código aos poucos quando for necessário                                        |
| R16 | Requisitos para nova MVP podem ser definidos de forma equivocada                             | Baixo         | Alto       | Sempre que possível, validar requisitos com o cliente     | Criar fluxo de criação, refinamento e validação de requisitos.                             |
| R17 | Priorizar etapas, requisitos ou atributos de qualidade de forma equivocada                   | Baixo         | Muito Alto | Validar dúvidas com o cliente                             | Despriorizar tudo que não for necessário                                                   |
| R18 | Tecnologia definida pode não atender requisitos do projeto                                   | Baixo         | Muito Alto | Enteder capacidade das tecnologias utilizadas             | Caso haja algum problema muito grande, estudar novas tecnologias e aplicá-las              |
| R19 | Requisitos do MVP podem não ser finalizados no prazo definido                                | Alto          | Muito Alto | Manter conversas frequentes com o cliente, validando os requisitos do MVP  | Caso seja necessário, reduzir e repriorizar os requisitos do MVP, para manter a entrega |

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSRNmajBsenuYzDO-3k0z0XIlA1UhBFF1FvxeuyMJThBsKcoyy4jSER5JkrHJf700FhHcpBohI3SO3b/pubhtml?gid=1173093087&amp;single=true&amp;widget=true&amp;headers=false" height="570px"></iframe> -->

## Refêrencia

> [1] TERLIZZI, Marco Alexandre; BIANCOLINO, César Augusto. <b>Estrutura Analítica de Riscos em Projetos de Desenvolvimento de Software no Setor Bancário: Um Estudo Exploratório</b>. Revista Gestão & Tecnologia, [S. l.], p. 51-78, 1 maio 2014. Disponível em: [revistagt.fpl.emnuvens.com.br/get/article/viewFile/628/534](revistagt.fpl.emnuvens.com.br/get/article/viewFile/628/534). Acesso em: 13 de nov. de 2022.

> [2] <b>Gerenciando os riscos do projeto com a matriz de probabilidade e impacto</b>. Disponível em: [https://glicfas.com.br/estrutura-analitica-de-riscos-2/](https://glicfas.com.br/estrutura-analitica-de-riscos-2/). Acesso em: 13 de nov. de 2022.

> [3] VARGAS, Ricardo; <b>Elaborando a Estrutura Analítica do Projeto (EAP/WBS) - Videocast</b>. Disponível em: [https://ricardo-vargas.com/pt/videos/videocast-preparing-the-work-breakdown-structure-wbs/](https://ricardo-vargas.com/pt/videos/videocast-preparing-the-work-breakdown-structure-wbs/). Acesso em: 3 jul. 2022.