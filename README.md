# Análise Cinematográfica para PProductions

Este projeto visa realizar uma análise detalhada de um banco de dados cinematográfico para orientar a PProductions na escolha do próximo tipo de filme a ser desenvolvido.

## Arquivo Jupyter Notebook

O projeto foi desenvolvido utilizando um arquivo Jupyter Notebook (`main.ipynb`), onde são explorados os dados, executados modelos de machine learning e feitas visualizações.

## Bibliotecas Utilizadas

- pandas
- numpy
- seaborn
- matplotlib.pyplot
- plotnine
- wordcloud
- collections
- sklearn (RandomForestRegressor, OneHotEncoder, LinearRegression, train_test_split, mean_squared_error, r2_score)
- joblib

## Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter Python 3 instalado. Recomenda-se a utilização de um ambiente virtual para gerenciar as dependências do projeto.


python -m venv venv

source venv/bin/activate  # No Windows use `venv\Scripts\activate`

## Instalação das Dependências

pip install -r requirements.txt

## Execução do Projeto

### Clone o repositório e execute o Jupyter Notebook

git clone https://github.com/seu_usuario/nome_do_repositorio.git
cd nome_do_repositorio

### Execute o Jupyter Notebook
jupyter notebook

### Abra e execute o arquivo main.ipynb no Jupyter Notebook.

## Arquivo de Requisitos
pip install -r requirements.txt

## Como Abrir Arquivos .pkl
import joblib

### Carregar um modelo treinado
model = joblib.load('nome_do_arquivo.pkl')

### Fazer previsões com o modelo
predictions = model.predict(dados_de_entrada)
