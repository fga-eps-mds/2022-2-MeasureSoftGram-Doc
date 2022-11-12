# Politica de Criação de Branches

## Histórico de Versões

Data|Versão|Descrição|Autor
-|-|-|-
10/11/2022|1.0|Abertura do documento |Rafael|
10/11/2022|1.0|Adição de introdução e do fluxo de trabalho|Rafael|
10/11/2022|1.0|Adição do tópico de branches e referências|Rafael|
12/11/2022|1.0|Revisão do documento |Nilvan|
12/11/2022|1.0|Retiradas da tag "< a>", que modificavam cor dos tópicos |Nilvan|

---

## 1. Introdução
<p align = "justify"> &emsp; Esse documento tem por objetivo padronizar a criação de branches nos repositório do MeasureSoftGram. Dessa forma, orientando a criação das ramificações do Git. </p>

---

## 2. Fluxo de trabalho
<p align = "justify"> &emsp; O fluxo de trabalho utilizado é o Gitflow Workflow [1]. Este é um modelo alternativo que traz uma ideia abstrata do fluxo de trabalho Git, orientando os tipos de ramificações e como fazer o merge. Basicamente, são criadas as ramificações de recurso ou funcionalidade, o que possibilita retardar o merge com a ramificação do tronco principal até as necessidades definidas no escopo para lançamento de uma versão [2]. Este fluxo de trabalho auxilia um software baseado em lançamento de versões, além de oferecer a possibilidade de consertar erros identificados em produção através de hotfixes. As ramificações são explicadas abaixo.</p>

---

## 3. Tipos de Branches
### 3.1 Main ou Master
<p align = "justify"> &emsp; Essa é a branch que contém o código mais estável do MeasureSoftGram, ou seja, o tronco principal. Tudo que o usuário consome da versão em produção se encontra nela. As diretrizes dela são:</p>

* Só existe <b>uma main/master</b> no projeto;
* Commits não são permitidos <b>diretamente</b> nessa branch;
* Mudanças nela só ocorrem por meio de pull requests das branches <b>release</b> ou <b>hotfix</b>.
* Em caso de repositório de documentação, aceita pull requests da branch <b>document</b>

### 3.3 Develop
<p align = "justify"> &emsp; Destinada ao desenvolvimento do projeto. Ou seja, toda novidade está nessa branch. Suas diretrizes são:</p>

* Só existe uma branch <b>develop</b> no projeto;
* Deve ser sincronizada com todas as outras branches;
* Deve ser derivada da main/master.

### 3.3 Document
<p align = "justify"> &emsp; Destinada à criação e manutenção dos documentos do projeto, ou seja, toda alteração no repositório de Doc do MeasureSoftGram, local principal dos documentos, passa por essa branch. Algumas regras diferem para esse tipo de branch, devido a própria natureza do repositório de documentação, o que implica:</p>

* Deve ser derivada da <b>main/master</b>;
* Deve ser mesclada a <b>main/master</b> aṕos documento ser concluído;
* Seu nome segue o padrão:

```
document/issueID-Nome_da_Funcionalidade
```

<p align = "justify">&emsp;&emsp;Onde:</p>

* <b>"document"</b> é padrão;
* <b>"issueID"</b> é o número da issue ao qual o documento se refere;

<p align = "justify">&emsp;&emsp;Exemplo:</p>

```
document/#88-Atualizar_Roadmap
```

### 3.4 Feature
<p align = "justify"> &emsp; Destinada à criação de uma nova funcionalidades ao projeto. Diretrizes:</p>

* Deve ser derivada da <b>develop</b>
* Deve ser mesclado de volta a <b>develop</b> após a funcionalidade ser desenvolvida;
* Toda nova funcionalidade tem sua própria branch, seguindo o seguite padrão de nome:

```
feature/issueID-Nome_da_Funcionalidade
```

<p align = "justify">&emsp;&emsp;Onde:</p>

* <b>"feature"</b> é padrão;
* <b>"issueID"</b> é o número da issue ao qual a funcionalidade se refere;

<p align = "justify">&emsp;&emsp;Exemplo:</p>

```
feature/#55-Criar_Feed_de_Notícias
```


### 3.5 Release
<p align = "justify"> &emsp; Branch que contém um conjunto de funcionalidades que podem ser implementadas na <b>main/master</b>. Diretrizes:</p>

* Deve ser derivada da <b>develop</b>;
* Após ser concluída deve ser mesclada na <b>main/master</b>;
* Nenhuma nova funcionalidade pode ser inserida na <b>main/master</b> se não por meio da <b>release</b>;
* Somente aceita mesclagens do tipo <b>bugfix</b>;
* O nome dessa branch deve seguir o padrão:

```
release/vNúmero.Número.Número
```

<p align = "justify">&emsp;&emsp;Onde:</p>

* <b>"release"</b> é padrão;

<p align = "justify">&emsp;&emsp;Exemplo:</p>

```
release/v1.0.0
```

### 3.6 Bugfix
<p align = "justify"> &emsp; Branch destinada a resolver problemas como bugs e erros presentes na <b>release</b>. Diretrizes:</p>

* Deve ser derivada da <b>release</b>;
* Deve ser mesclada a release após concluída;
* Seu nome segue o seguinte padrão:

```
bugfix/issueID-Nome_do_bugfix
```

<p align = "justify">&emsp;&emsp;Onde:</p>

* <b>"bugfix"</b> é padrão;
* <b>"issueID"</b> é número da issue ao qual o bugfix se relaciona;

<p align = "justify">&emsp;&emsp;Exemplo:</p>

```
bugfix/#89-Resolver_Feed_de_Noticias
```

### 3.7 Hotfix
<p align = "justify"> &emsp; Destinada a resolver problemas urgentes na <b>master</b>. Diretrizes:</p>

* Deve ser derivada da <b>master</b>;
* Dever ser mesclada a <b>main/master</b> após concluída;
* A cada novo <b>hotfix</b>, a versão do produto deve ser modificado, incrementando uma unidade ao número extremo direito.
* O nome segue o seguinte padrão:

```
hotfix/vNúmero.Número.Número
```

<p align = "justify">&emsp;&emsp;Onde:</p>

* <b>"hotfix"</b> é padrão;

<p align = "justify">&emsp;&emsp;Exemplo:</p>

```
hotfix/v1.0.1
```

---

## 4. Referências

> [1] DRIESSEN, Vincent. A successful Git branching model. [S. l.], 5 jan. 2010. Disponível em: <a href="https://nvie.com/posts/a-successful-git-branching-model/">https://nvie.com/posts/a-successful-git-branching-model/</a>. Acesso em: 10 nov. 2022.

> [2] GITFLOW Workflow. [S. l.], 201-. Disponível em: <a href="https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow">https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow</a>. Acesso em: 10 nov. 2022.
