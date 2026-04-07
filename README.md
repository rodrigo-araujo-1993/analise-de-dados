# Análise de Dados – Taxas de Homicídio e Desenvolvimento

Este repositório apresenta um projeto de análise exploratória de dados focado na relação entre taxas de homicídio e indicadores de desenvolvimento humano ao redor do mundo.

## Objetivo

Investigar dois pontos principais:

- Em que medida taxas de homicídio baseadas em prevalência podem distorcer a análise da violência
- Qual é a relação entre homicídios e indicadores de desenvolvimento, como expectativa de vida e anos de escolaridade

---

## Estrutura do repositório

- `MVP_Visualização_e_análise_de_dados_...ipynb`  
  Notebook principal com toda a análise

- `Dataset 1 - Homicide Statistics.xlsx`  
  Dados de taxas de homicídio

- `dataset_HDI_filtered.xlsx`  
  Indicadores de desenvolvimento humano

- `population_worldbank.csv`  
  Dados populacionais utilizados para análise e suavização

---

## Principais análises realizadas

- Análise exploratória dos dados (EDA)
- Identificação de outliers e assimetria
- Transformação logarítmica das taxas de homicídio
- Aplicação de técnicas de suavização
- Análise de correlação entre variáveis
- Comparação entre dados originais e ajustados

---

## Principais insights

- Taxas de homicídio baseadas em prevalência podem ser altamente instáveis, especialmente em países com menor população  
- Outliers têm forte impacto nas análises e podem distorcer correlações  
- Após suavização, as relações observadas se tornam mais estáveis e realistas  
- Existe uma relação negativa entre desenvolvimento e taxas de homicídio, embora não necessariamente causal  

---

## Tecnologias utilizadas

- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  

---

## Como executar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/analise-de-dados.git
