# Plano de Qualidade do Produto

## Versionamento

| Data       | Versão | Descrição                                                                | Autor(es)   |
| ---------- | ------ | ------------------------------------------------------------------------ | ----------- |
| 27/11/2022 | 0.1    | Criação do documento                                                     | Ítalo Alves |
| 27/11/2022 | 1.0    | Adição dos tópicos de introdução e objetivos do plano                    | João Moura  |
| 27/11/2022 | 1.1    | Adição dos objetivos de qualidade e tópico sobre verificação e validação | João Moura  |
| 27/11/2022 | 1.2    | Adição tópico inicial de métricas e referências                          | João Moura  |
| 28/11/2022 | 1.3    | Adição dos tópicos de Testes e Controle de Código                        | Ítalo Alves |
| 29/11/2022 | 1.4    | Adição dos tópicos de Métricas, Ferramentas e Coleta                     | Ítalo Alves |

## Introdução

<p align="justify" style="text-indent: 20px">
Não só Escopo, Tempo e Custo influênciam no gerênciamento de projetos de software, mas também os atributos de qualidade. Segundo ISO 9126-1 (2003) [<a href=./#referencia>1</a>], "qualidade é a totalidade de características e critérios de um produto ou serviço que exercem suas habilidades para satisfazer às necessidades declaradas ou envolvidas", mostrando dessa forma a importância dessa característica para o gerênciamento do projeto.
</p>

## Objetivos do Plano de Qualidade

<p align="justify" style="text-indent: 20px">
Para entender melhor o planejamento da qualidade no projeto, esse documento visa, portanto, especificar procedimentos, técnicas e ferramentas que serão utilizadas para que os requisitos de qualidade sejam contemplados durante o desenvolvimento do projeto. Para mensurar e acompanhar essa evolução de qualidade serão utilizadas em especial métricas, avaliando, dessa forma, quantitativamente.
</p>

<p align="justify" style="text-indent: 20px">
Com isso, definem-se os principais objetivos desse documento, sendo eles:
</p>

- Definir os objetivos da qualidade
- Apresentar maneiras para atingir os objetivos
- Selecionar e utilizar métricas para a aferição
- Interpretar os resultados do uso das métricas
- Especificar procedimentos, técnicas e ferramentas utilizadas

## Objetivos de qualidade

<p align="justify" style="text-indent: 20px">
Seguindo os objetivos propostos nas ISO 9126-1 de 2003, dois serão os pontos focais da análise de qualidade do projeto: a <b>qualidade interna e externa</b> e a <b>qualidade de uso</b>.
</p>

- <p align="justify">
  A <b>qualidade interna e externa</b> tem como principal objetivo avaliar o produto, através de 6 características principais (Funcionalidade, Confiabilidade, Usabilidade, Eficiência, Manutenabilidade e Portabilidade), divididas em diversas subcaracterĩ́sticas. Essas subcaracterísticas são manifestadas externamentes quando o software é utilizado, sendo resultantes de atributos internos do produto.
  </p>

- <p align="justify">
  Por sua vez, a <b> qualidade de uso</b> especifica apenas 4 principais características (Eficácia, Produtividade, Segurança e Satisfação), obtidas pela combinação das 6 características de qualidade (interna e externa) definidas previamentes pela ISO.
  </p>

## Verificação e validação

<p align="justify" style="text-indent: 20px">
Entendendo os objetivos de qualidade que desejam ser atendidos no projeto, parte-se para a definição de como os mesmos serão atingidos. Para isso, as técnicas de verificação e validação podem ser utilizadas, em específico três delas foram selecionadas inicialmente para a sua utilização:
</p>

- <p align="justify">
  <b>Análise estática do código</b>: Essa primeira técnica envolve a utilização de ferramentas de análise estática de código para a obtenção de métricas que podem ser avalidas e quantificadas. A ferramenta Sonar Cloud foi selecionada para realizar essa ação, gerando informações importantes para a gerência de qualidade do projeto.
  </p>

- <p align="justify">
  <b>Testes automatizados</b>: Além da análise estática, a documentação por testes automatizados (unitários e de integração), também foi utilizada para a realização do gerênciamento. Por meio dessa técnica, a equipe consegue validar não apenas os caminhos esperados, mas também situações de erros que são importantes de serem tratados.
  </p>

- <p align="justify">
  <b>Validações com os donos do projeto</b>: Por fim, uma validação que não envolve o contato direto com linhas de código é a validação com os donos/usuários do projeto. Essa propõe que através de reuniões semanais, seja validado o que já está pronto e com isso decisões sobre o rumo do produto (priorizações) sejam tomadas mais facilmente.
  </p>

## Padrões, práticas, convenções e métricas

<p align="justify" style="text-indent: 20px">
A existência de padrões de software, tem garantido cada vez mais qualidade no desenvolvimento do produto, já que conseguem identificar as melhores práticas. Com isso, a utilização de métricas permite a identificação de padrões de código que não são desejaveis nos produto final, pois não seguem padrões previamente definidos. Apesar disso, é importante ressaltar que mesmo essas métricas serem universalmente aplicaveis, tudo depende dos objetivos de qualidade esperados no produto.
</p>

### ISOs e Modelos de Qualidade

<p align="justify" style="text-indent: 20px">
Como principal ISO e modelo utilizados no projeto, pode-se citar:
</p>

- NBR - ISO/IEC 9126-1 [<a href=./#referencia>1</a>]
- Modelo de Qualidade Q-Rapids [<a href=./#referencia>2</a>]

<p align="justify" style="text-indent: 20px">
Além disso, os seguintes modelos podem ser citados como bibliografia:
</p>

- QUAMOCO [<a href=./#referencia>3</a>]
- SQuale
- QATCH
- QuASE

### Métricas

<p align="justify" style="text-indent: 20px">
Para medir a qualidade do software, deve-se determinar quais características medir e como medir (Boehm, 1981) [<a href=./#referencia>4</a>]. Portanto, utilizando-se das métricas é possível derivar as subcaracterísticas e consequentemente as características do produto avaliado, indicando sua qualidade, avaliando sua produtividade e aferindo resultados que podem ser decisivos para o rumo do projeto.
</p>

<p align="justify" style="text-indent: 20px">
Para tanto, as seguintes métricas [<a href=./#referencia>5</a>] foram definidas para o projeto:
</p>

<center>

| Métrica                  | Descrição                                           |
| ------------------------ | --------------------------------------------------- |
| Files                    | Quantidade de arquivos de código                    |
| Functions                | Quantidade de funções no código                     |
| Complexity               | Complexidade ciclomática                            |
| Comment Lines Density    | Densidade (%) de linhas comentadas                  |
| Duplicated Lines density | Densidade (%) de linhas duplicadas                  |
| Coverage                 | Cobertura de código pelos testes                    |
| Ncloc                    | Quantidade de linhas de código                      |
| Tests                    | Testes unitários e de integração                    |
| Test Errors              | Teste que possuem erros                             |
| Test Failures            | Testes que falharam                                 |
| Test Execution Time      | Tempo de execução dos testes                        |
| Security Rating          | Avaliação de segurança de falhas e vulnerabilidades |

</center>

### Métricas para o produto

<p align="justify" style="text-indent: 20px">
Com os valores coletados das métricas, temos um indicativo sobre a qualidade do produto. Dessa forma, é possível definir valores mínimos aceitáveis para cada métrica, fazendo com que o produto atenda pelo menos esses indicativos.

Para definir os valores das métricas aceitáveis selecionadas, para a qualidade interna, usamos como base as métricas definidas no Q-rapids e SonarCloud indicadas abaixo:

</p>

<center>

| Metrica                      | Valor        |
| ---------------------------- | ------------ |
| Complexity                   | até 10       |
| Comment Lines Density (%)    | até 30%      |
| Duplicated Lines Density (%) | até 5%       |
| Coverage                     | acima de 60% |
| Test Failures                | 0            |
| Test Errors                  | 0            |
| Security Rating              | 0 (A)        |
| Satisfação do usuário        | acima de 3   |

</center>

## Testes

<p align="justify" style="text-indent: 20px">
Testes de software é um conjunto de processos com os quais se pretende validar um sistema ou aplicação, em momentos diferentes, para verificar seu correto funcionamento. São uma série de procedimentos que visam encontrar possíveis bugs, reportar erros, identificar problemas de usabilidade, bem como assegurar que todos os requisitos solicitados pelo cliente sejam atendidos. [<a href=./#referencia>6</a>]
</p>
Alguns tipos de testes de software:

- Teste de Unidade: É utilizado para validar se um pedaço do código está funcionando corretamente;
- Teste de Integração: É utilizado para verificar a integração correta entre os diferentes componentes;
- Teste de Caixa-Branca: Garante a análise de todos os caminhos independentes de cada módulo, programa ou método;
- Teste Caixa-Preta: É utilizado para verificar todas as entradas e saídas desejadas.

## Ferramentas, técnicas e metodologias

- [Pytest](https://docs.pytest.org/en/latest/): Framework de testes para Python;
- [Jest](https://jestjs.io/): Framework de testes para TypeScript;
- [ESLint](https://eslint.org/): Ferramenta de verificação de código, que garante que o código esteja de acordo com os padrões encontrados no ECMAScript;
- [Prettier](https://prettier.io/): Ferramenta formatadora de código;
- [Codecov](https://codecov.io/): Ferramenta que verifica cobertura de código;
- [SonarCloud](https://sonarcloud.io/): Ferramenta de varredura de código para analisar o código de acordo com as regras e métricas definidas.

## Controle de código

<p align="justify" style="text-indent: 20px">
O controle do código-fonte (ou controle de versões) é a prática de monitoramento e gerenciamento de alterações no código. Para garantir os procedimentos de qualidade, estão sendo realizadas tarefas automatizadas, como: documentação, controle de versão, controle de código, testes automatizados, controle de commits e outros.
</p>

## Referência

> [1] **NBR - ISO/IEC 9126-1**. Software engineering - Product quality - Part 1: Quality model. 2003.

> [2] **Quality-aware Rapid Software Development Project: The Q-Rapids Project**. FRANCH X.; LOPEZ L.; FERNÁNDEZ S. M.; ORIOL M.; RODRÍGUEZ P.; TRENDOWICZ A.

> [3] **A Quality Model for Actionable Analytics in Rapid Software Development**. FERNÁNDEZ S. M.; JEDLITSCHKA A.; GUZMÁN L.; VOLLMER A. M. Kaiserslautern, Alemanha.

> [4] **Software Engineering Economics**. BOEHM B. 1981.

> [5] **Metric Definitions**. SonarQube. Disponível em: [https://docs.sonarqube.org/latest/user-guide/metric-definitions/](https://docs.sonarqube.org/latest/user-guide/metric-definitions/). Acesso em: 27 nov. 2022.

> [6] **Importância dos testes de software na qualidade do sistema**. TreinaWeb. Disponível em: [https://www.treinaweb.com.br/blog/importancia-dos-testes-de-software-na-qualidade-do-sistema](https://www.treinaweb.com.br/blog/importancia-dos-testes-de-software-na-qualidade-do-sistema). Acesso em: 28 nov. 2022.
