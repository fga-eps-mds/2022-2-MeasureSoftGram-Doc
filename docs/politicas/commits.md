# Política de commits

## Histórico de Versões

Data|Versão|Descrição|Autor
-|-|-|-
10/11/2022|1.0|Abertura do documento com template inicial|Rafael|
12/11/2022|1.1|Adição do commit em inglês para repositórios de desenvolvimento de código|Rafael|
12/11/2022|1.2|Adição do commit de hotfix|Rafael|

## Políticas de Commits
<p style="text-align: justify; text-indent: 20px">Os commits devem ser feitos de maneira clara e objetiva respeitando os padrões comentados a seguir: </p>

### Repositório de Documentação
<ul>
    <li> Devem estar escritos em português. </li>
    <li> Os verbos devem estar no gerúndio. </li>
    <li> Devem apresentar o número base da issue ou começar com hotfix. </li>
</ul>

&emsp;Portanto a formatação do commit será: ` #2 Corrigindo imagem quebrada no documento de visão `
<p style="text-align: justify; text-indent: 20px">Vale a pena lembrar que é possível utilizar o seguinte Hook já configurado para esse repositório, que acrescentará automaticamente o número da Branch em seu commit:</p>

```bash
#!/bin/sh
BRANCH=$(git branch | grep "*" | sed 's/* \([0-9]*\)-.*/#\1/')
TEXT=$(cat "$1" | sed '/^#.*/d')

if [ -z "$BRANCH" ]
then
    echo "Branch não esta no formato NUMERO-TITULO_ISSUE."
fi

if [ -n "$TEXT" ]
then
    echo "$BRANCH" "$TEXT" > $1
else
    echo "Commit sem mensagem."
    exit 1
fi
```
&emsp;Para adicioná-lo, basta criar um arquivo chamado `pre-commit` na pasta `.git/hooks` 
e torná-lo um arquivo executável com o comando `chmod +x pre-commit`.

### Repositório de Código
<ul>
    <li> Devem estar escritos em inglês. </li>
    <li> Os verbos devem estar no gerúndio. </li>
    <li> Devem apresentar o número base da issue ou começar com hotfix. </li>
</ul>

&emsp;Portanto a formatação do commit será: ` #45 Adding name field in login form `

### Múltiplos responsáveis pelo commit

<p style="text-align: justify; text-indent: 20px">E por fim, nas ocasiões em que o commit for realizado por duas ou mais pessoas, deve ser acrescentado à mensagem do commit o seguinte texto: </p>

```
Co-authored-by: Fulano Sousa <fulanosousa@gmail.com>
```

<p style="text-align: justify; text-indent: 20px">Este texto deve estar disposto duas linhas abaixo do título do commit.</p>
