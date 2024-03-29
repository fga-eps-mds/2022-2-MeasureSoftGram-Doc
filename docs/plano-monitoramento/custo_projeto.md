# Custos de projeto

## Versionamento

| Data | Versão | Descrição | Autor(es) |
|------|------|------|------|
|13/11/2022|1.0|Criação do documento| João Victor Valadão, Lucas Melo, João Pedro Moura, Ítalo Fernandes |
|15/11/2022|1.1|Atualizado custos por universitário e custos com equipamentos| Lucas Melo |
|22/11/2022|1.2|Adicionado EVM| Lucas Melo |
|22/11/2022|1.3|Atualizado link evm| Lucas Melo |
|25/11/2022|1.4|Correções do documento e melhoria das tabelas| João Pedro Moura, Rafael Cleydson |
|26/11/2022|2.0|Refatoração do tópico e planilha do EVM| João Pedro Moura, Rafael Cleydson |
|05/02/2023|2.1|Atualização da planilha e da referência do EVM| João Pedro Moura, Rafael Cleydson |

## Introdução

<p align="justify" style="text-indent: 20px">Esse documento tem como objetivo explanar os custos estimados para o desenvolvimento do projeto. Essa  estimativa levará em consideração o tempo de desenvolvimento definido no cronograma do projeto, o custo de um aluno de graduação da Universidade de Brasília e demais custos envolvidos.
</p>

## Custo por universitário

<p align="justify" style="text-indent: 20px">
Usando  como referência a reportagem Raio-X do custo por aluno nas universidades federais, publicada pelo jornal O Globo em 2016 [<a href=./#referencia>1</a>], o custo de um aluno da Universidade de Brasília é de R$ 38.805,00 por ano.</p>

<p align="justify" style="text-indent: 20px">
Utilizando a calculadora de ajuste de inflação do Banco Central do Brasil [<a href=./#referencia>2</a>] para calcular o valor atualizado para o ano de 2022. Para isso foi utilizado o índice de inflação IPCA (IBGE) usando os anos de 2016 e 2022. O resultado foi de R$ 53.140,65, sendo assim o custo mensal de R$ 4.428,39. Considerando que cada aluno cursa em média 6 matérias(360 horas) por semestre, o custo de um aluno por disciplina é de R$ 738,06. Levando em conta que a disciplina que o projeto é desenvolvido possui 60 horas, temos que cada aluno custaria por hora R$ 12,30.
</p>

<p align="justify" style="text-indent: 20px">Considerando que cada membro do grupo irá trabalhar em média 40 horas por mês no projeto, e que o o projeto tem duração de 90 dias úteis (ou 4 meses). Com 11 integrantes o custo total estimado no desenvolvimento do projeto seja aproximadamente de <b>R$ 5.412,47</b></p>

## Custo de internet

<p align="justify" style="text-indent: 20px">Considerando que todos os integrantes do time possuem internet banda larga, de pelo menos 100 MBPS, os valores estimados para Brasília foram de:</p>

| Mensal por aluno | Mensal por grupo    | 4 meses      |
| ---------------- | --------------      | -------      |
| R$ 100.00        | R$ 1100.00          | R$ 3300.00   |


## Custo de água

| Mensal por aluno | Mensal por grupo    | 4 meses      |
| ---------------- | --------------      | -------      |
| R$ 50.00         | R$ 550.00           | R$ 2200.00   |


## Custo de Energia

| Mensal por aluno | Mensal por grupo    | 4 meses      |
| ---------------- | --------------      | -------      |
| R$ 71.00         | R$ 781.00           | R$ 3124.00   |

## Custo de equipamentos

<p align="justify" style="text-indent: 20px">Para realizar a estimativa de custo de equipamentos, foi considerando que o único equipamento necessário para o desenvolvimento do projeto é um computador com as seguintes especificações:</p>

* Deve possuir um processador Intel Core i5 da 11ª geração ou superior;
* Deve possuir 8 GB de memória RAM ou superior;
* Deve possuir SSD de 256 GB ou superior;


<p align="justify" style="text-indent: 20px">Usando como base essas especificações de hardware, um Notebook Acer Aspire 5 A515-54G-55HW Intel Core I5 8GB 256GB SSD Windows 11 15,6” Prata teria o custo de <b>R$ 3.699,00</b>. Sendo assim, para 11 participantes, o custo total de <b>R$ 40.689,00.</b></p>

## Earned Value Management (EVM)

<p align="justify" style="text-indent: 20px">
Para ter uma avaliação mais completa dos custos durante todo o curso do projeto, optou-se por utilizar a análise ágil EVM (<i>Earned Value Management</i> ou Gestão de Valor Agregado). Essa técnica faz a medição de três principais fatores do projeto: Custos, Tempo e Escopo, podendo ser expandida para utilizar outras características como qualidade [<a href=./#referencia>3</a>].
</p>

<p align="justify" style="text-indent: 20px">
Através de cada <i>sprint</i> do projeto, três métricas serão coletadas: Valor Planejado (VP), Valor Agregado (VA) e Custo Atual (CA), sendo utilizadas para o cálculo e análise dos custos do projeto. Toda a análise pode ser acessada por aqui <a href='https://docs.google.com/spreadsheets/d/e/2PACX-1vT3rHd0sywGAqNVUB26yKJGPKO5lHDWYpCsK1WDwUwbnl6-9-V4WmqEBnthWo1D_5EWaiUFpL5qlTZq/pubhtml?widget=true&amp;headers=false'>aqui</a> ou pela visualização abaixo:
</p>

<iframe style="width: 100%; height: 500px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT3rHd0sywGAqNVUB26yKJGPKO5lHDWYpCsK1WDwUwbnl6-9-V4WmqEBnthWo1D_5EWaiUFpL5qlTZq/pubhtml?widget=true&amp;headers=false"></iframe>


## Referência

> [1] **RAIO-X DO CUSTO POR ALUNO NAS UNIVERSIDADES FEDERAIS**. Disponível em: [https://infograficos.oglobo.globo.com/brasil/raio-x-do-custo-por-aluno-nas-universidades-federais.html](https://infograficos.oglobo.globo.com/brasil/raio-x-do-custo-por-aluno-nas-universidades-federais.html). Acesso em 13 nov. 2022.

> [2] **BCB - Calculadora do cidadão**. Bcb.gov.br. Disponível em: [https://www3.bcb.gov.br/CALCIDADAO/publico/corrigirPorIndice.do?method=corrigirPorIndice](https://www3.bcb.gov.br/CALCIDADAO/publico/corrigirPorIndice.do?method=corrigirPorIndice). Acesso em: 16 nov. 2022.

 > [3] **AgileEVM – Earned Value Management in Scrum Projects**. Tamara S.; Brent B.; Thomas B. Proceedings of AGILE 2006 Conference. 2006.
