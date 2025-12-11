# Análise de Vendas de Café: Exploratory Data Analysis (EDA)

Este projeto apresenta uma análise exploratória dos dados de vendas de uma cafeteria ao longo de aproximadamente um ano, utilizando Python (Pandas, Matplotlib e Seaborn). O objetivo é entender padrões de consumo, desempenho de produtos e sazonalidade temporal, gerando insights práticos para negócios.

---

## Sobre o Dataset

O conjunto de dados utilizado é público e está disponível no Kaggle:
Coffee Sales – Kaggle Dataset
https://www.kaggle.com/datasets/ihelon/coffee-sales

Ele contém 3.636 registros de vendas entre março/2024 e março/2025 e as principais colunas são:

- `date` – data da venda  
- `datetime` – horário da venda  
- `cash_type` – forma de pagamento  
- `money` – valor da transação  
- `coffee_name` – tipo de café vendido  

A estrutura permite análises tanto por produto quanto temporais.

---

## Objetivos

A análise busca responder a questões como:

- Quais produtos têm maior volume de vendas e maior faturamento?
- Como as vendas variam ao longo do tempo (diário, semanal, mensal)?
- Há padrões de sazonalidade ou recorrência?
- Como o preço médio se comporta entre diferentes tipos de café?
- Existem dias da semana com melhor ou pior desempenho?
- Quais insights podem apoiar decisões estratégicas?

---

## Principais Resultados

### Análise de Produtos
- Os produtos com maior volume de vendas foram:
  - *Americano with Milk* (824)
  - *Latte* (782)
  - *Americano* (578)
- Em receita total, os principais itens foram:
  - *Latte* (R$ 27.866,30)
  - *Americano with Milk* (R$ 25.269,12)
  - *Cappuccino* (R$ 18.034,14)
- Em ticket médio, destacaram-se:
  - *Hot Chocolate* (R$ 36,07)
  - *Cappuccino* (R$ 36,00)
  - *Cocoa* (R$ 35,71)

### Análise Temporal
- Os maiores faturamentos mensais foram observados em:
  - **Outubro de 2024** (R$ 13.891,16)
  - **Fevereiro de 2025** (R$ 13.215,48)
- O menor mês foi **janeiro de 2025** (R$ 6.398,86)
- Entre os dias da semana, **terça-feira** teve maior receita total.

---

## Insights de Negócio

Com base na análise, algumas ações potenciais incluem:

- Concentrar campanhas de marketing em meses historicamente mais fortes.  
- Utilizar o Espresso como item de entrada para atrair novos clientes.  
- Criar descontos ou combos em dias tradicionalmente mais fortes, como terça-feira.  
- Planejar ações específicas para aumentar o movimento aos domingos.  
- Automatizar relatórios mensais para acompanhamento contínuo do desempenho.  

---

## Próximos Passos

- Incorporar dados de custo para análise de margem por produto.  
- Explorar segmentação de clientes utilizando dados de pagamento.  
- Desenvolver um modelo simples de previsão de vendas.  
- Automatizar relatórios mensais com Python.

---

## Ferramentas Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  
