# 📊 Challenge - Telecom: Análise de Evasão de Clientes

Este repositório contém a solução para o *Challenge* de Data Science da formação da Alura. O objetivo principal é analisar o comportamento dos clientes de uma empresa de telecomunicações, com foco especial na **evasão (churn)**, utilizando técnicas de análise exploratória de dados e visualização.

## 📁 Arquivo

- `Challenge_Telecomx.ipynb`: Notebook Jupyter com todo o processo de análise exploratória, incluindo limpeza de dados, visualizações e interpretação dos principais padrões relacionados à evasão de clientes.

## 🎯 Objetivos do Projeto

- Entender o perfil dos clientes que mais tendem a deixar a empresa.
- Explorar variáveis demográficas, contratuais e financeiras.
- Visualizar padrões e correlações que ajudem na formulação de estratégias para reduzir a evasão.
- Apresentar as descobertas de forma visual e acessível.

## 🧪 Etapas Desenvolvidas

### 1. **Preparação dos Dados**
- Leitura e visualização do dataset.
- Limpeza e normalização de colunas.
- Criação de variáveis auxiliares como `Qtd_Servicos` e `Gasto_Diario`.

### 2. **Análise Exploratória**
- Visualização da evasão por:
  - Tipo de contrato
  - Método de pagamento
  - Uso de serviços (internet, suporte técnico, fatura online etc.)
  - Perfil do cliente (idoso, com dependentes ou parceiro)
- Análise da taxa de evasão em função da **quantidade de serviços contratados**.
- Avaliação da **correlação** entre variáveis numéricas e a evasão.
- Análises individuais de variáveis contínuas via **boxplots** e **distribuições KDE**.

### 3. **Principais Ferramentas Utilizadas**
- `pandas` para manipulação de dados
- `matplotlib` e `seaborn` para visualizações

## 📈 Visualizações em Destaque

- **Heatmap de Correlação:** destaca as variáveis numéricas mais associadas à evasão.
- **Gráficos de barras agrupadas:** mostram o impacto de variáveis categóricas na evasão.
- **Boxplots e histogramas com KDE:** revelam a distribuição dos gastos e tempo de contrato para clientes que evadiram ou permaneceram.

## 📌 Conclusões (Resumo)

- Certos tipos de contrato e métodos de pagamento estão fortemente relacionados com maiores taxas de evasão.
- Clientes com menos serviços contratados tendem a evadir mais.
- Gastos mensais e tempo de contrato influenciam significativamente a permanência do cliente.

---

## 💡 Como Executar

1. Clone este repositório
2. Abra o notebook `Challenge_Telecomx.ipynb` em um ambiente Jupyter (JupyterLab, VSCode, Google Colab, etc.)
3. Execute as células sequencialmente

---

## 👩‍💻 Autor
Allie Vellani

Projeto desenvolvido como parte do desafio da formação da Alura em Data Science.

