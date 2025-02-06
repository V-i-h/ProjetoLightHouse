<<<<<<< HEAD
# 🚀 **Projeto de Previsão de Preços - Programa Lighthouse Indicium**

Este projeto foi desenvolvido como parte do processo seletivo para o **Programa Lighthouse Indicium**, com foco na **carreira de Cientista de Dados**.

## 🎯 **Objetivo do Projeto**

Desenvolver um modelo de previsão de **preços de imóveis** utilizando um dataset fornecido. O modelo foi treinado para prever o preço com base em características do imóvel.

## 📂 **Arquivos Disponíveis**

- **`teste_indicium_precificacao.csv`**: Contém os dados dos imóveis utilizados para a análise e treinamento do modelo.
- **`LH_CD_VITÓRIA_SILVA.pkl`**: Arquivo com o modelo treinado de **RandomForestRegressor**, pronto para ser utilizado em previsões de preços.

## ⚙️ **Instalação**

Este projeto foi desenvolvido com **Python 3.13.1**. Para garantir que o ambiente esteja configurado corretamente, siga as etapas abaixo.

### 1. **Clonar o Repositório**

Clone o repositório para sua máquina local:

### 2. **Instalar as Dependências**

pip install -r requirements.txt

### 3. **Reiniciar o Jupyter Notebook**

Após a instalação das dependências, reinicie o Jupyter Notebook para garantir que todas as bibliotecas sejam carregadas corretamente.

### 4. **Executando o Projeto no Google Colab**

Caso queira executar o projeto no Google Colaboratory, basta carregar o arquivo CSV teste_indicium_precificacao.csv no seu Google Drive.

1. Carregue o arquivo CSV no seu Google Drive.
2. No seu notebook do Google Colab, monte o drive e acesse o arquivo com o código:

from google.colab import drive
drive.mount('/content/drive')

🧠 Modelo de Previsão
O projeto inclui um modelo treinado de RandomForestRegressor, salvo no arquivo LH_CD_VITÓRIA_SILVA.pkl. Caso seu objetivo seja apenas realizar previsões, siga as etapas abaixo para carregar e usar o modelo.

Carregando o Modelo Treinado
Para carregar o modelo em seu próprio notebook e realizar previsões, basta executar o seguinte código:

import pickle

# Carregar o modelo treinado
modelo_rfr = pickle.load(open('LH_CD_VITÓRIA_SILVA.pkl', 'rb'))

# Realizar a previsão com o modelo carregado
previsao = modelo_rfr.predict(X_teste)




