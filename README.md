# 💳 Predição de Churn em Serviços de Cartão de Crédito Bancário

![Banner do Projeto](https://github.com/giuliabugatti09/bank_credit_card_churn_predicition/blob/main/images/foto_capa.jpeg)

## 📌 Visão Geral
Projeto de machine learning para prever cancelamento de cartões de crédito, desenvolvido por **Giulia Bugatti**. O modelo alcança **85% de precisão** na identificação de clientes com risco de churn, permitindo ações proativas de retenção.

## 🔍 Principais Características
✔ Modelo preditivo com **XGBoost e LightGBM**  
✔ Análise detalhada dos **principais drivers de churn**  
✔ Pipeline completo de **pré-processamento e feature engineering**  
✔ Cálculo de **impacto financeiro** das previsões  
✔ Visualizações interativas de **desempenho do modelo**  

## 📊 Métricas de Desempenho
| Métrica          | Valor  |
|------------------|--------|
| **Acurácia**     | 89%    |
| **Precisão**     | 85%    |
| **Recall**       | 82%    |
| **F1-Score**     | 0.83   |
| **ROC-AUC**      | 0.91   |

![Matriz de Confusão](images/Matriz_confusao_erros.png)

## 🛠️ Stack Tecnológica
### 💻 Linguagens & Frameworks
![Python](https://img.shields.io/badge/Python-3.11+-3776AB?logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2+-F7931E?logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-1.7+-017CEE?logo=xgboost)
![LightGBM](https://img.shields.io/badge/LightGBM-3.3+-0FAA4F)

### 📊 Processamento de Dados
![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-1.24+-013243?logo=numpy)

### 📈 Visualização
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7+-11557C?logo=matplotlib)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-5B8FA8)
![Plotly](https://img.shields.io/badge/Plotly-5.14+-3F4F75?logo=plotly)

## 🎯 Problema de Negócio
**Contexto:** Taxa de churn de 16% nos cartões de crédito  
**Objetivo:** Reduzir custos de aquisição (CAC) e aumentar valor vitalício (CLV)  
**Solução:** Modelo preditivo para identificar clientes em risco  

![Taxa de Cancelamento](images/taxa_cancelamento.png)

## 🔍 Insights Principais
- Clientes com **menos transações** e **baixo gasto médio** têm maior risco
- **Atrasos em pagamentos** são fortes indicadores de churn
- Cartões básicos e clientes **jovens** cancelam mais
- **Tempo de relacionamento** é fator protetor contra churn

![Correlações](images/matriz_de_correlacao.png)

## ⚙️ Pipeline da Solução
1. **Coleta de dados** (Kaggle dataset)
2. **Análise exploratória** (EDA completo)
3. **Feature engineering** (20+ features criadas)
4. **Modelagem comparativa** (5 algoritmos testados)
5. **Otimização** (Hyperparameter tuning)
6. **Análise de impacto financeiro**

![Curva ROC](images/Curva_ROC.png)

## 💰 Impacto Financeiro
**Estimativa de ganho:** \$171,477  
**Estratégias:**
- 10% de desconto para clientes de alto risco (VP)
- 8% de desconto para falsos positivos
- Evitar perda total (18%) em falsos negativos

## 🚀 Como Executar
```bash
git clone https://github.com/giuliabugatti09/bank_credit_card_churn_predicition.git
cd bank_credit_card_churn_predicition
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt
python application.py
```

## 📂 Estrutura do Projeto
```
bank_credit_card_churn_predicition/
├── data/                   # Dados brutos e processados
├── notebooks/              # Análises exploratórias
├── images/                 # Visualizações
├── requirements.txt        # Dependências
└── README.md               # Documentação
```

## 📊 Visualizações
1. **Distribuição de Features**  
   ![Distribuição](images/Distribuição_recursos_numéricos.png)

2. **Análise de Variáveis Categóricas**  
   ![Categóricas](images/Distribuicao_caracteristicas_categoricas.png)

3. **Comparação de Modelos**  
   ![Modelos](images/Linear_Models.png)

## 🤝 Como Contribuir
1. Faça um fork do projeto
2. Crie sua branch (`git checkout -b feature/nova-melhoria`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-melhoria`)
5. Abra um Pull Request

## 📜 Licença
Distribuído sob a licença MIT. Veja [LICENSE](LICENSE) para detalhes.

## ✉️ Contato
**Giulia Bugatti**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Giulia_Bugatti-blue?logo=linkedin)](https://www.linkedin.com/in/giulia-bugatti-fonseca-226955267/)  
[![GitHub](https://img.shields.io/badge/GitHub-giuliabugatti09-black?logo=github)](https://github.com/giuliabugatti09)  
[![Email](https://img.shields.io/badge/Email-giuliabugatti02%40gmail.com-red?logo=gmail)](mailto:giuliabugatti02@gmail.com)

---

**Dataset:** [Kaggle Credit Card Customers](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)  
**Última atualização:** Junho 2025
