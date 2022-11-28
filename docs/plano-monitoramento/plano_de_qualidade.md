# Plano de Qualidade do Produto

## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|27/11/2022|0.1|Criação do documento| Ítalo Alves |
|27/11/2022|1.0|Adição dos tópicos de introdução e objetivos do plano| João Moura|
|27/11/2022|1.1|Adição dos objetivos de qualidade e tópico sobre verificação e validação | João Moura|

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

