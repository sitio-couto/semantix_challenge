# Desafio Data Science

## Arquivos

* `/bank` - Contém os [*datasets* utilizados](​https://archive.ics.uci.edu/ml/datasets/bank+marketing).
* `/Data_Science_Challenge.ipynb` - Jupyter notebook com todas as análises para resolução dos exercícios.
* `/data_science_challenge.py` - Script em Python do código no notebook.
* `/requirements.txt` - Versões das blibiotecas utilizadas.


## Perguntas e Respostas

### **1. Qual profissão tem mais tendência a fazer um empréstimo? De qual tipo?**

A profissão com maior tendência de empréstimos é '*blue-collar*', sendo que '*housing loans*' é o tipo mais comum.

### **2. Fazendo uma relação entre número de contatos e sucesso da campanha quais são os pontos relevantes a serem observados?**

Em geral, contatar múltiplas vezes um indivíduo não compensa, pois alcança um número menor de pessoas, e não garante maior taxa de sucesso, fazendo com que tanto o valor absoluto quanto o relativo de sucessos sejam maiores para casos em que foram feitos poucos contatos.

### **3. Baseando-se nos resultados de adesão desta campanha qual o número médio e o máximo de ligações que você indica para otimizar a adesão?**

A média de ligações deve ser próxima à uma por pessoa, já que apresenta melhor taxa de sucesso, e o máximo seriam quatro ligações, uma vez que o número de sucessos aproxima-se de seu mínimo deste ponto em diante.

### **4. O resultado da campanha anterior tem relevância na campanha atual?**

A partir da análise, podemos assumir que o resultado da campanha anterior é relevante para atual. Seria benéfico, por exemplo, dar prioridades a indivíduos que já participaram de alguma campanha pois teriam maior probabilidade de sucesso em relação aos que não participaram.

### **5. Qual o fator determinante para que o banco exija um seguro de crédito?**

O fator determinante para exigência de seguro de crédito aparenta ser a idade do cliente, uma vez que quase não há ocorrências de pessoas menores que 21 ou maiores que 60 sem exigência de seguro de crédito, e que esta é a idade empregatícia.

### **6. Quais são as características mais proeminentes de um cliente que possua empréstimo imobiliário?**

A idade e o emprego do indivídou são as características mais relevantes ao se avaliar se este apresenta ou não empréstimo imobiliário. O perfil destes costuma ser *blue-collars* de 30 a 50 anos de idade.

## *Referências*

1. [Panda's Documentation Reference](https://pandas.pydata.org/pandas-docs/stable/)

1. [Panda's groupby() Function Reference](https://www.shanelynn.ie/summarising-aggregation-and-grouping-data-in-python-pandas/)

2. [Matplotlib Plotting Reference](https://matplotlib.org/)

3. [Seaborn Confusion Matrix Plot](https://gist.github.com/shaypal5/94c53d765083101efc0240d776a23823)

5. [Feature Importance Techniques](https://towardsdatascience.com/feature-selection-techniques-in-machine-learning-with-python-f24e7da3f36e)

6. [Weight of Evidence and Information Value](https://towardsdatascience.com/attribute-relevance-analysis-in-python-iv-and-woe-b5651443fc04)