# 🚀 Telecom X - Modelagem de Machine Learning para Prever Churn

## 📋 Descrição do Projeto

Este projeto implementa um pipeline completo de **Machine Learning** para prever **churn** (evasão) de clientes na Telecom X. Como Analista de Machine Learning Júnior, você desenvolverá modelos preditivos capazes de identificar quais clientes têm maior probabilidade de cancelar seus serviços.

## 🎯 Objetivos

✅ **Preparar dados** para modelagem (tratamento, encoding, normalização)  
✅ **Realizar análise** de correlação e seleção de variáveis  
✅ **Treinar modelos** de classificação (Regressão Logística, Random Forest, Gradient Boosting)  
✅ **Avaliar desempenho** com métricas apropriadas  
✅ **Interpretar resultados** e importância das variáveis  
✅ **Criar conclusão estratégica** com insights acionáveis  

## 🧰 Tecnologias Utilizadas

- **Python 3.8+**
- **Pandas & NumPy** - Manipulação de dados
- **Scikit-learn** - Machine Learning
- **Matplotlib & Seaborn** - Visualizações
- **Jupyter Notebook** - Ambiente de desenvolvimento

## 📁 Estrutura do Projeto

```
challenge/
├── TelecomX_Data.json          # Dados originais da Telecom X
├── TelecomX_dicionario.md      # Dicionário de dados
├── TelecomX_BR.ipynb           # Análise exploratória (EDA)
├── TelecomX_ML_Modeling.ipynb  # 🆕 Modelagem de ML
├── requirements.txt             # Dependências do projeto
└── README_ML.md                # Este arquivo
```

## 🚀 Como Executar

### 1. Instalar Dependências
```bash
pip install -r requirements.txt
```

### 2. Executar o Notebook
```bash
jupyter notebook TelecomX_ML_Modeling.ipynb
```

### 3. Executar Célula por Célula
- Execute cada célula sequencialmente
- Aguarde a conclusão de cada etapa
- Verifique os resultados e visualizações

## 📊 Pipeline de Machine Learning

### 🔧 **Etapa 1: Preparação dos Dados**
- Carregamento e limpeza dos dados
- Conversão de tipos de dados
- Criação de variáveis derivadas
- Tratamento de valores nulos

### 🔍 **Etapa 2: Análise Exploratória**
- Análise de correlação entre variáveis
- Seleção de features mais relevantes
- Visualizações informativas

### 🎯 **Etapa 3: Modelagem**
- **Regressão Logística** - Modelo linear interpretável
- **Random Forest** - Modelo ensemble robusto
- **Gradient Boosting** - Modelo de boosting avançado

### 📈 **Etapa 4: Avaliação**
- Métricas de performance (Acurácia, F1-Score, ROC-AUC)
- Matriz de confusão
- Curvas ROC comparativas
- Validação cruzada

### 🔍 **Etapa 5: Interpretação**
- Importância das variáveis
- Coeficientes dos modelos
- Insights estratégicos
- Recomendações acionáveis

## 📋 Variáveis Utilizadas

### **Features Principais:**
- `tenure` - Tempo de contrato
- `Charges.Monthly` - Cobrança mensal
- `Charges.Total` - Cobrança total
- `ContractDuration` - Duração do contrato
- `TotalServices` - Total de serviços contratados
- `SeniorCitizen` - Cliente idoso
- `OnlineSecurity` - Segurança online
- `TechSupport` - Suporte técnico

### **Target:**
- `Churn` - Indicador de evasão (0 = permaneceu, 1 = saiu)

## 🏆 Resultados Esperados

- **Modelos treinados** com performance otimizada
- **Métricas de avaliação** comparativas
- **Ranking de variáveis** mais importantes
- **Insights estratégicos** para redução de churn
- **Recomendações acionáveis** para a equipe de negócios

## 📈 Métricas de Avaliação

- **Acurácia** - Proporção de predições corretas
- **F1-Score** - Média harmônica entre precisão e recall
- **ROC-AUC** - Capacidade de discriminação do modelo
- **Matriz de Confusão** - Detalhamento dos erros

## 🎯 Aplicações Práticas

- **Sistema de alertas** para clientes em risco
- **Campanhas de retenção** personalizadas
- **Otimização de serviços** baseada em padrões
- **Dashboard de monitoramento** em tempo real
- **Estratégias de fidelização** direcionadas

## 🔮 Próximos Passos

1. **Implementação** do modelo em produção
2. **Monitoramento contínuo** da performance
3. **Refinamento** baseado em novos dados
4. **Expansão** para outros segmentos de clientes
5. **Integração** com sistemas de CRM

## 👨‍💻 Autor

**Analista de Machine Learning Júnior** - Vitória Gomes <br>
**Data:** Agosto 2025  
**Missão:** Desenvolver soluções preditivas para redução de churn

