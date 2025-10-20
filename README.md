# Projeto de Análise Preditiva de Preços de Imóveis (House Prices - Kaggle)

## Descrição e Objetivo
Este projeto demonstra um ciclo completo de **Data Science**, com foco em:  
- Análise Exploratória de Dados (EDA)  
- Engenharia de Recursos (Feature Engineering)  
- Modelagem Preditiva (Regressão Avançada)  

O objetivo não foi apenas prever o preço de venda, mas **identificar e comunicar os principais fatores (drivers)** que influenciam o valor de um imóvel, traduzindo resultados complexos de Machine Learning em insights claros para o negócio.

---

## Habilidades Técnicas e Ferramentas
- **Python:** Pandas, NumPy  
- **Visualização:** Matplotlib, Seaborn  
- **Modelagem Preditiva:** XGBoost  
- **Validação:** Cross-Validation (CV)

---

## Principais Gráficos do Projeto

### Visualização de Dados Faltantes
Mostra as colunas com maior quantidade de dados ausentes e a proporção de missing values:  

<img width="989" height="490" alt="Visualização de Dados Faltantes" src="https://github.com/user-attachments/assets/dace7622-e63f-45d9-89be-911a74798f27" />

---

### Importância das Features
Top 10 variáveis mais importantes para prever o preço de venda dos imóveis:  

<img width="989" height="590" alt="Importância de Features" src="https://github.com/user-attachments/assets/f43a8be6-aa6c-4878-84c5-b906f9ba1e66" />

---

## Conclusões e Destaques

1. **Feature Engineering e Tratamento de Dados:**  
   Criação de variáveis de alto impacto, como `TotalSF`, e imputação lógica de dados faltantes baseada em análise visual.  

2. **Interpretabilidade do Modelo:**  
   O gráfico de importância de features mostra que **Qualidade Geral (OverallQual)** e **Área Total (TotalSF)** são os fatores-chave que determinam o preço do imóvel.  

3. **Robustez Comprovada:**  
   Validação Cruzada (CV) garante que o modelo seja estável, generalize bem e não apresente overfitting.  
