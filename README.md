# # Análise e Predição de Ratings de K-Dramas

Este repositório contém um notebook Jupyter (`.ipynb`) que realiza a análise e a predição dos ratings de K-Dramas com base em diversas variáveis, como duração dos episódios, número de episódios, atores, gênero, entre outros. O projeto utiliza uma **Rede Bayesiana** para prever a variável "Rating", que representa a avaliação média dos usuários no website MyDramaList.

## Objetivo

O principal objetivo do projeto é prever a classificação (rating) dos K-Dramas com base nas variáveis disponíveis, utilizando um modelo de Rede Bayesiana e avaliando a precisão das predições.

## Estrutura do Projeto

- `Prevendo Avaliações Médias de K-Dramas.ipynb`: Notebook Jupyter contendo toda a análise, processamento de dados e modelagem do problema. O notebook inclui as seguintes etapas:
  1. Descrição do problema, dados e variáveis.
  2. Pré-processamento dos dados, incluindo transformação de variáveis quantitativas em qualitativas.
  3. Construção e ajuste da Rede Bayesiana.
  4. Predição e avaliação da qualidade do modelo utilizando o erro absoluto médio (MAE).
  
## Requisitos

Para rodar o notebook localmente, você precisará ter o Python instalado, juntamente com as bibliotecas abaixo:

- `pandas`
- `numpy`
- `scikit-learn`
- `pgmpy` (para modelagem da Rede Bayesiana)
- `matplotlib` (para visualização)

Você pode instalar os requisitos executando:

```bash
pip install pandas numpy scikit-learn pgmpy matplotlib
