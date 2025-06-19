# DataScience

# 📊 Projeto Final - Análise do Dataset "50 Startups"

Este repositório contém o projeto final da disciplina de Ciência de Dados, com foco em análise de dados, seleção de variáveis e construção de um modelo de regressão para prever o lucro de startups americanas com base em seus investimentos.

## 📁 Estrutura

- `ProjetoDSParteIII_Vasques.ipynb` — Notebook principal com todo o código, análises e visualizações.
- `50_Startups_dataset.csv` — Base de dados utilizada (fornecida via Kaggle).
- `README.md` — Este arquivo com informações sobre o projeto.

---

## 🎯 Objetivo

Responder às seguintes perguntas com base no dataset "50 Startups":

1. O investimento em P&D influencia diretamente o lucro?
2. Marketing impacta significativamente o lucro?
3. Gastos administrativos têm correlação com o lucro?
4. O estado onde a startup opera afeta os resultados?

---

## 🔍 Etapas Desenvolvidas

### 1. Análise Exploratória
- Verificação de valores ausentes
- Análise gráfica das distribuições
- Matriz de correlação
- Análise de outliers com boxplot

### 2. Seleção de Features
- Utilização do método `SelectKBest` com `f_regression` para selecionar as variáveis mais relevantes.

### 3. Modelagem
- Modelo utilizado: **Regressão Linear**
- Divisão em treino/teste (80/20)
- Treinamento com `LinearRegression` do `sklearn`

### 4. Avaliação do Modelo
- **R² (coeficiente de determinação)**
- **MAE (Erro Absoluto Médio)**
- **MSE (Erro Quadrático Médio)**
- **RMSE (Erro Quadrático Médio Raiz)**

---

## 📈 Resultados

O modelo apresentou bom desempenho, explicando uma alta proporção da variabilidade no lucro das startups. O investimento em **P&D** se destacou como a variável mais relevante, seguido por marketing.

---

## 📝 Conclusões

- A regressão linear foi adequada para esse tipo de problema.
- A seleção de features reduziu a complexidade sem sacrificar a performance.
- Análises gráficas revelaram padrões importantes para interpretação dos dados.
- O projeto cumpre todos os requisitos da proposta.

---

## 🚀 Como Executar

1. Clone este repositório
2. Abra o notebook `ProjetoDSParteI_Vasques.ipynb` no Jupyter ou Google Colab
3. Certifique-se de que o arquivo `50_Startups_dataset.csv` esteja acessível no mesmo diretório ou modifique o caminho

---

## 👨‍💻 Autor

Igor Renato da Fonseca Vasques  
[LinkedIn](https://www.linkedin.com/in/igor-vasques-10b46191//) | [GitHub](https://github.com/henkrj)

