# 🏦 Bank Marketing Project
### Predição de Subscrição de Depósitos a Prazo com Machine Learning

---

## 📘 Introdução

O **Bank Marketing Project** tem como objetivo prever a probabilidade de um cliente bancário subscrever um **depósito a prazo**, com base em dados históricos de campanhas de marketing direto realizadas por um banco português.

Utilizando técnicas de **ciência de dados e machine learning**, o projeto analisa o comportamento dos clientes, identifica os fatores mais relevantes para a decisão e constrói modelos preditivos capazes de apoiar a segmentação de campanhas futuras.

---

## 📊 Objetivos Principais

- Analisar e compreender padrões nos dados de campanhas bancárias  
- Tratar e preparar os dados para modelagem supervisionada  
- Treinar e comparar diferentes modelos de classificação  
- Avaliar o desempenho e selecionar o modelo mais robusto  
- Interpretar variáveis-chave que influenciam a decisão dos clientes  

---

## 🧩 Etapas do Projeto

### 1. Análise Exploratória de Dados (EDA)
- Visualização de distribuições e correlações entre variáveis  
- Análise de comportamento dos clientes por idade, profissão, saldo e contacto  
- Identificação de classes desbalanceadas no *target*  

### 2. Pré-Processamento
- Limpeza e transformação de dados  
- Codificação *one-hot* para variáveis categóricas  
- Normalização dos dados numéricos  
- Balanceamento das classes com **SMOTE (Synthetic Minority Over-sampling Technique)**  

### 3. Modelagem
Foram treinados e comparados vários algoritmos de classificação:  
- **Logistic Regression**  
- **Decision Tree Classifier**  
- **Random Forest Classifier**  
- **Gradient Boosting Classifier**  
- **XGBoost Classifier**  

### 4. Avaliação de Desempenho
**Métricas utilizadas:**  
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

**Visualizações incluídas:**  
- Matriz de confusão  
- Curva ROC  
- Feature Importance (importância das variáveis)  

---

## 🏆 Resultados Principais

O modelo **XGBoost** apresentou o melhor desempenho, alcançando:  
- **ROC-AUC:** 0.91  
- **F1-score:** 0.88  

As variáveis mais influentes incluíram:  
- Duração da chamada última chamada
- Número de contactos na campanha anterior 
- Saldo anual médio
- Idade
  
---

## 🧠 Conclusão

O projeto demonstra como técnicas de *machine learning* podem ser aplicadas para aumentar a eficácia de campanhas de marketing bancário, permitindo:  
- Otimizar o direcionamento de clientes;  
- Reduzir custos de campanhas ineficazes;  
- Maximizar a taxa de conversão em depósitos a prazo.  

---

## ⚙️ Tecnologias Utilizadas

| Categoria | Ferramentas |
|------------|--------------|
| Linguagem | Python 3 |
| Manipulação de dados | Pandas, NumPy |
| Visualização | Matplotlib, Seaborn |
| Modelagem | Scikit-learn, XGBoost, Imbalanced-learn |
| Exportação de métricas | openpyxl, pandas |
| Ambiente | Jupyter Notebook |

---

## 📂 Estrutura do Projeto
```
📁 Bank_Marketing_Project/
│
├── 📁 DataProcessed/            # Dados tratados após o pré-processamento
├── 📁 Metrics_Tables/           # Tabelas de métricas exportadas (Excel)
├── 📁 Models/                   # Modelos treinados (ficheiros .pkl)
│
├── 📄 Bank_Marketing-Project.ipynb   # Notebook principal com análise e modelagem
├── 📄 ExportMetricsToExcel_1.py      # Script para exportar resultados e métricas
├── 📄 requirements.txt               # Dependências do projeto
```

---

## 🚀 Como Executar o Projeto

### 1️⃣ Pré-requisitos
- Python 3.8+  
- Jupyter Notebook  
- Instalar dependências:
```bash
pip install -r requirements.txt
```

### 2️⃣ Executar o Notebook
```bash
jupyter notebook Bank_Marketing-Project.ipynb
```

---

## 👤 Autor
**Filipe Araújo Melo**  
📧 Email: melofilipe4@hotmail.com] 
