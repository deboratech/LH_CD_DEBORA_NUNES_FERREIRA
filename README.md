# # Análise Cinematográfica para PProductions
Este projeto visa realizar uma análise detalhada de um banco de dados cinematográfico para orientar a PProductions na escolha do próximo tipo de filme a ser desenvolvido.

# Bibliotecas Utilizadas
- pandas
- numpy
- seaborn
- matplotlib.pyplot
- plotnine
- wordcloud
- collections
- sklearn (RandomForestRegressor, OneHotEncoder, LinearRegression, train_test_split, mean_squared_error, r2_score)
- joblib

# Instalação e Execução do Projeto
Pré-requisitos
Certifique-se de ter Python 3 instalado. Recomenda-se a utilização de um ambiente virtual para gerenciar as dependências do projeto.

python -m venv venv
source venv/bin/activate  # No Windows use `venv\Scripts\activate`

# Instalação das Dependências
pip install -r requirements.txt

# Execução do Jupyter Notebook
Clone o repositório:
git clone https://github.com/seu_usuario/nome_do_repositorio.git
cd nome_do_repositorio

# Execute o Jupyter Notebook:
jupyter notebook

# Abra e execute o arquivo main.ipynb no Jupyter Notebook.
Arquivo de Requisitos
O arquivo requirements.txt contém todas as bibliotecas utilizadas e suas versões específicas. Para instalar as dependências, utilize o comando:
pip install -r requirements.txt

# Como Abrir Arquivos .pkl
Os arquivos .pkl podem ser carregados utilizando a biblioteca joblib no Python. Exemplo:
import joblib

Carregar um modelo treinado
model = joblib.load('random_forest_regressor_model.pkl') 

Fazer previsões com o modelo
predictions = model.predict(dados_de_entrada)

# Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou reportar problemas.
