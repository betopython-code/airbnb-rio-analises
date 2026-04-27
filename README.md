# 🏠 Airbnb Rio de Janeiro - Análise de Dados

## 📌 Sobre o projeto

Este projeto realiza uma análise exploratória de dados reais do Airbnb na cidade do Rio de Janeiro, com o objetivo de entender padrões de preços, distribuição de imóveis e comportamento dos anúncios.

Os dados foram obtidos através do projeto Inside Airbnb, que disponibiliza datasets públicos para análise.

---

## 🎯 Problema de Negócio

O mercado de aluguel por temporada possui grande variação de preços e tipos de imóveis. Este projeto busca responder:

* Quais regiões possuem os imóveis mais caros?
* Qual tipo de hospedagem é mais vantajoso?
* Existe relação entre preço e popularidade (reviews)?
* Onde há maior concentração de imóveis?

---

## 🛠️ Tecnologias utilizadas

* Python
* Pandas
* Matplotlib
* Seaborn
* Folium (mapas interativos)

---

## 📊 Principais Análises

### 📍 Preço médio por bairro

Identificação dos bairros com maior valor médio de hospedagem.

### 🏡 Tipo de imóvel

Comparação entre:

* Imóvel inteiro
* Quarto privado
* Quarto compartilhado

### ⭐ Preço vs Número de Reviews

Análise da relação entre valor da diária e popularidade do anúncio.

### 🗺️ Mapa interativo

Visualização geográfica dos imóveis com base em latitude e longitude.

---

## 📌 Principais Insights

* Bairros da Zona Sul apresentam os maiores preços médios
* Imóveis inteiros possuem valores significativamente mais altos
* A concentração de imóveis é maior em regiões turísticas
* Não há forte correlação entre preço e número de reviews

---

## 📸 Visualizações

### 🗺️ Mapa de imóveis

![Mapa Airbnb](images/mapa_airbnb.png)

---

## 📁 Estrutura do projeto

```
airbnb-rio-analysis/
│
├── data/
├── notebooks/
├── images/
├── requirements.txt
└── README.md
```

---

## ▶️ Como executar

1. Clone o repositório:

```
git clone https://github.com/betopython-code/airbnb-rio-analises
```

2. Instale as dependências:

```
pip install -r requirements.txt
```

3. Execute o notebook:

```
jupyter notebook
```

---

## 📎 Fonte dos dados

Inside Airbnb: http://insideairbnb.com/

---

## 👨‍💻 Autor

Roberto Ramos Pereira

