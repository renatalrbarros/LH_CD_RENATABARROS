# LH_CD_RENATABARROS
Desafio envolvendo análise exploratória e modelagem de conceitos básicos de  Machine Learning, com relatório, notebooks e modelo salvo em .pkl.
Projeto de Análise Exploratória e Modelagem

Este projeto contém uma análise exploratória de dados (EDA), a modelagem de um algoritmo de Machine Learning para prever notas de filmes, além do modelo salvo em formato .pkl.

Respositório:
meu-projeto/
│── README.md              <- este arquivo
│── requirements.txt       <- bibliotecas necessárias
│── notebooks/
│   ├── 01_EDA.ipynb       <- análise exploratória
│   ├── 02_Modelagem.ipynb <- treino e avaliação do modelo
│── reports/
│   └── analises.pdf       <- relatório em PDF com EDA
│── models/
│   └── modelo.pkl         <- modelo treinado salvo

⚙️ Instalação

- Clone o repositório:

git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd SEU_REPOSITORIO


- Crie um ambiente virtual (opcional, mas recomendado):

python -m venv venv


- Ative o ambiente:

Linux/Mac: source venv/bin/activate

Windows: venv\Scripts\activate

Instale as dependências:

pip install -r requirements.txt

- Como executar

- Abra os notebooks na pasta notebooks/ para ver a análise e a modelagem:

jupyter notebook


O relatório em PDF pode ser acessado diretamente em reports/analises.pdf.

O modelo treinado está disponível em models/modelo.pkl e pode ser carregado em Python assim:

import pickle

with open("models/modelo.pkl", "rb") as f:
    modelo = pickle.load(f)

# exemplo de previsão
y_pred = modelo.predict(X_novos_dados)

- Tecnologias utilizadas

Python 3.x

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

Jupyter Notebook

Autora:

Projeto desenvolvido por Renata Barros.
