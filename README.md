# _Previsão de sobrevivência do Titanic_

Este projeto consiste em uma análise preditiva da sobrevivência de passageiros do Titanic utilizando técnicas de aprendizado de máquina. O objetivo é construir um modelo que consiga prever se um passageiro sobreviveu ou não com base em características pessoais e sociais.

## _Estrutura do Projeto_

### _Pré-processamento de Dados:_
- _Leitura das bases de dados de treino e teste._
- _Limpeza dos dados, incluindo a remoção de colunas irrelevantes e o tratamento de valores ausentes._
- _Criação de novas funcionalidades, como indicadores de gênero e se o passageiro estava sozinho ou não._

### _Transformação de Dados:_
- _Aplicação de escaladores (RobustScaler) para normalizar variáveis numéricas._
- _Utilização de codificadores (OrdinalEncoder) para converter variáveis categóricas em um formato numérico adequado para modelos de aprendizado de máquina._

### _Divisão dos Dados:_
- _Separação da base de dados de treino em conjuntos de treino e validação._

### _Modelagem:_
- _Treinamento de diferentes modelos de classificação: Regressão Logística, Random Forest e MLP Classifier (Redes Neurais)._
- _Avaliação do desempenho de cada modelo utilizando estatísticas como acurácia e matriz de confusão._

### _Previsão:_
- _Aplicação do modelo mais eficaz na base de teste para prever a sobrevivência dos passageiros._
- _Geração de um arquivo CSV com a variação para submissão._

## _Tecnologias Utilizadas_
- _Linguagem de Programação: Python_
- _Bibliotecas: Pandas, Scikit-learn, Matplotlib, Seaborn_

## _Objetivo_
_O objetivo deste projeto é demonstrar a capacidade de aplicar técnicas de aprendizado de máquina para resolver problemas do mundo real, utilizando um conjunto de dados conhecidos e explorando as diversas etapas de pré-processamento, modelagem e avaliação._
