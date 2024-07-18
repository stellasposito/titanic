# 📝 Análise Exploratória Titanic

Este é um projeto que teve início durante a minha pós-graduação em Ciências de Dados na Facens, mas foi finalizado com algumas partes extras por interesse e curiosidade própria.

> Algumas colunas foram excluídas por não se encaixarem nas análises.
> 
>  Colunas disponíveis neste dataset:
> 

  Survived (Sobreviveu): 0 = Não, 1 = Sim

  Pclass (Classe): Classe de ingresso 1 = 1º, 2 = 2º, 3 = 3º

  Sex (Sexo): Sexo do passageiro
  
  Age (Idade): Idade em anos
  
  Sibsp: Quantidade de irmãos / cônjuges a bordo do Titanic
  
  Parch: Quantidade de pais / crianças a bordo do Titanic
  
  Ticket (Bilhete): Número do bilhete de embarque
  
  Fare (Tarifa): Tarifa paga pelo Passageiro
  
  Embarked (Embarque): Porto de Embarque (C = Cherbourg, Q = Queenstown, S = Southampton)



##  📝 Teorema de Bayes e Algoritmo Naive Bayes

Uma das partes interessantes deste projeto foi poder treinar a utilização da Probabilidade Condicional com o Teorema de Bayes e o algoritmo de Machine Learning Naive Bayes. 
Esses cálculos foram realizados para analisar a probabilidade de uma pessoa sobreviver levando em consideração o sexo e a classe em que estava viajando. 

Para a análise com o Naive Bayes, a variável X foi definida como a coluna Sex e a coluna Pclass (classe de viagem no navio), e a variável y foi definida como a coluna Survived (considerando apenas os sobreviventes para a análise, Survived = 1).


## 🚀 Insights! 

Com muitas análises estatísticas e gráficas, gostaria de compartilhar alguns insights deste dataset: 

> 1º A maioria dos passageiros eram adultos (foram consideradas pessoas acima de 15 anos e abaixo de 60);
> 
> 2º Pessoas com 29 anos tiveram a maior taxa de mortalidade, pois muitas linhas da coluna Age estavam com valores faltantes e foi substituído pela média (29);
> 
> 3º A classe 1 era mais cara, portanto, apresentava mais adultos e idosos do que crianças;
> 
> 4º A probabilidade de sobrevivência tanto de homens quanto de mulheres da classe 3 era a mais baixa.    
