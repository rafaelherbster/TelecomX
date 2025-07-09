# 📊 Análise de Churn de Clientes - TelecomX

Este projeto tem como objetivo realizar uma análise exploratória dos dados de clientes da empresa fictícia **TelecomX**, com foco na identificação de padrões e características associadas ao **Churn** (cancelamento de contrato).

## 📁 Dataset

- Fonte: [TelecomX Dataset](https://raw.githubusercontent.com/ingridcristh/challenge2-data-science/refs/heads/main/TelecomX_Data.json)
- Formato: JSON
- Total de entradas: **7.267 clientes**
- Total de variáveis: **21 colunas**

## 🧪 Objetivos da Análise

- Entender o perfil dos clientes que cancelaram o serviço (`Churn = Yes`)
- Verificar a distribuição das variáveis quantitativas e qualitativas
- Identificar possíveis correlações entre as variáveis
- Criar visualizações para facilitar a interpretação dos dados
- Gerar insights que ajudem na **retenção de clientes**

---

## 🔍 Análises Realizadas

### 📌 Classificação das Variáveis

As variáveis do conjunto de dados foram classificadas da seguinte forma:

- **Quantitativas Contínuas**: `MonthlyCharges`, `TotalCharges`, `DailyCharges`
- **Quantitativas Discretas**: `Tenure`
- **Qualitativas Nominais**: `customerID`, `Gender`, `MultipleLines`, `InternetService`, `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`, `StreamingTV`, `StreamingMovies`, `PaymentMethod`, `Churn`, `Contract`
- **Qualitativas Binárias**: `SeniorCitizen`, `Partner`, `Dependents`, `PhoneService`, `PaperlessBilling`

---

## 📊 Visualizações

- **Gráficos de barras** para análise das variáveis qualitativas
- **Histogramas e boxplots** para variáveis quantitativas
- **Heatmap de correlação**
- Distribuição da média e mediana para comparação de assimetrias
- Comparação entre `MonthlyCharges`, `DailyCharges` e `TotalCharges`

---

## 💡 Insights Principais

- **Clientes com menor tempo de contrato (Tenure)** tendem a cancelar mais.
- Há uma forte correlação entre **TotalCharges** e o tempo de permanência (`Tenure`).
- Clientes se dividem em dois grupos: com planos básicos e com serviços avançados (distribuição bimodal).
- Variáveis como `OnlineSecurity`, `TechSupport` e `Streaming` estão fortemente associadas ao perfil dos clientes.

---

## 📈 Ferramentas Utilizadas

- **Python** com as bibliotecas:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `plotly`
  - `math`
  - `IPython.display.Markdown`
  - `request`

---

## 🧠 Conclusão

A análise permite identificar perfis de clientes com maior propensão ao churn e fornece informações estratégicas para:
- Criar campanhas de retenção mais eficazes
- Oferecer planos personalizados
- Otimizar a jornada do cliente com base em dados

---

## 🚀 Próximos Passos

- Aplicar modelos preditivos (machine learning) para prever churn
- Testar estratégias de segmentação
- Avaliar impacto de ações sobre a base de clientes

---

## 📌 Autor

- **Rafael Herbster de Sena Maciel**  
- Contato: [rafaelherbster8@gmail.com](mailto:rafaelherbster8@gmail.com)  
- [LinkedIn](https://www.linkedin.com/rafael-herbster) • [GitHub](https://github.com/rafaelherbster)


