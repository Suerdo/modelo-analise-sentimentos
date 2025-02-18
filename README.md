# Análise de Sentimentos com Processamento de Linguagem Natural e Machine Learning

Este projeto desenvolve um modelo de análise de sentimentos utilizando técnicas de Processamento de Linguagem Natural (NLP) e Aprendizado de Máquina. O objetivo é classificar textos como positivos ou negativos, sendo aplicável a contextos como análise de feedbacks, monitoramento de redes sociais e processamento de opiniões de usuários.

## Tecnologias Utilizadas

- **Python**
- **Pandas** – Manipulação e análise de dados
- **NLTK** – Processamento de Linguagem Natural
- **Scikit-learn** – Modelos de Machine Learning
- **WordCloud** – Visualização de palavras mais frequentes
- **TfidfVectorizer** – Transformação de textos em representações numéricas
- **Bag of Words** – Técnica de representação de texto

## Estrutura do Projeto

### 1. Pré-processamento dos Dados  
- Importação e visualização do conjunto de dados
- Remoção de stopwords
- Remoção de pontuações e acentos
- Tokenização e normalização

### 2. Transformação de Texto em Dados Numéricos  
- Conversão dos textos utilizando **Bag of Words** e **TF-IDF**
- Análise das features mais relevantes

### 3. Treinamento do Modelo  
- Aplicação de algoritmos de Machine Learning
- Testes com diferentes classificadores
- Ajuste de hiperparâmetros para otimização do desempenho

### 4. Avaliação e Resultados  
- Cálculo de métricas de desempenho, como acurácia, precisão e recall
- Identificação dos termos mais influentes na classificação

## Desempenho do Modelo  

O modelo apresentou um desempenho satisfatório, atingindo uma **acurácia de 91.85%** na classificação de sentimentos. Esse resultado indica que o modelo é capaz de distinguir entre textos positivos e negativos com alta precisão, tornando-o adequado para aplicações práticas como análise de avaliações de produtos, redes sociais e atendimento ao cliente.

A análise das métricas também demonstrou um equilíbrio entre precisão e recall, garantindo que o modelo minimize tanto falsos positivos quanto falsos negativos.
