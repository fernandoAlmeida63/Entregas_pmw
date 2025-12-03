# Entregas_pmw
# 🚀 Previsão de Tempo de Entrega Olist

## 🎯 Objetivo do Projeto
Este projeto utiliza uma **Rede Neural (TensorFlow/Keras)** para prever o tempo de entrega de pedidos da Olist, medida em minutos. O foco foi na Engenharia de Features para utilizar dados logísticos reais (distância, peso, frete e tempo prometido).

## 📊 Metodologia
1.  **Datasets Utilizados:** orders, items, customers, geolocation, sellers e products.
2.  **Features Chave:** Distância Haversine (KM), Valor do Frete, Peso/Volume do Produto, Tempo Prometido pela Olist e Sazonalidade (Mês/Dia).
3.  **Modelo:** Rede Neural Sequencial (Dense(128), Dense(64), Dense(32)).
4.  **Otimização:** Função de Perda **MAE** e Regularização **Dropout (0.2)**.

## 📈 Resultados (MAE)
O modelo final atingiu um Erro Absoluto Médio (MAE) de **6720.79 minutos**, o que equivale a aproximadamente **4.67 dias**.

## 🛠️ Como Rodar o Notebook
1.  Clone este repositório.
2.  Instale as dependências: `pip install -r requirements.txt`
3.  Carregue os datasets da Olist no seu ambiente.
4.  Execute as células do `notebook_olist_entregas.ipynb`.
