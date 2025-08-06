# 📊 Telecom X - Análise de Evasão de Clientes

Este projeto foi desenvolvido como parte do **Desafio de Data Science** do programa Oracle Next Education (ONE), com o objetivo de analisar o problema de **evasão de clientes (churn)** da empresa fictícia **Telecom X**.

---

## 🎯 Objetivo

A Telecom X enfrenta um alto índice de cancelamento de contratos. Neste desafio, o foco é aplicar o processo de **ETL (Extração, Transformação e Carga)** e realizar uma **Análise Exploratória de Dados (EDA)** para:

- Compreender o comportamento dos clientes
- Identificar os fatores que levam à evasão
- Apoiar a criação de modelos preditivos
- Gerar recomendações estratégicas para reduzir o churn

---

## 🛠️ Tecnologias Utilizadas

- **Python 3**
- **Google Colab**
- **Bibliotecas:**
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `json`

---

## 📁 Fonte dos Dados

Os dados estão hospedados no GitHub em formato JSON e foram carregados diretamente no notebook via URL raw.

- 🔗 [Acessar JSON (raw)](https://raw.githubusercontent.com/ingridcristh/challenge2-data-science/refs/heads/main/TelecomX_Data.json)

---

## 📈 Etapas do Projeto

### 1. Extração
- Leitura dos dados JSON diretamente da URL utilizando `pandas.read_json()`.

### 2. Transformação
- Tratamento de dados ausentes e duplicados
- Conversão e padronização de tipos
- Preparação dos dados para análise

### 3. Análise Exploratória (EDA)
- Visualização de distribuições e correlações
- Comparações entre grupos de clientes (ex: com e sem churn)
- Geração de insights com base em dados demográficos, serviços contratados, formas de pagamento e fidelidade

---

## 🔍 Principais Insights

- Clientes com **contratos mensais** têm maior tendência de evasão.
- A ausência de **serviços adicionais** e de **fidelidade contratual** está relacionada ao churn.
- O **método de pagamento** também influencia o comportamento de evasão.

---

## ✅ Conclusões e Recomendações

Com base na análise realizada, recomenda-se que a empresa:

- Incentive a migração para contratos anuais
- Ofereça pacotes com serviços adicionais para aumentar o engajamento
- Crie campanhas de retenção para os primeiros meses de contrato
- Estude melhorias nos métodos de pagamento, especialmente para clientes com churn alto

---

## ▶️ Execução

Você pode executar e explorar o projeto diretamente no Google Colab:

[![Abrir no Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/https://colab.research.google.com/drive/1D09hrEL1pVHAlBTpfo4QbkrmpnynQWPC#scrollTo=6XnTC2NTmMRL)

---

## 👩🏽‍💻 Desenvolvido por

**Fernanda Braz**  
Assistente de Análise de Dados – Desafio ONE  
- 🌐 [GitHub](https://github.com/Fernandabrazz)  
- 💼 [LinkedIn](https://linkedin.com/in/fernandabrazz)

---

## 📄 Licença

Projeto desenvolvido exclusivamente para fins educacionais, como parte do Programa ONE em parceria com a Alura.
