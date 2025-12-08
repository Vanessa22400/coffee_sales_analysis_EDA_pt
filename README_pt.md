# Análise de Vendas de Café — Exploratory Data Analysis (EDA)

Este projeto apresenta uma análise exploratória de vendas de uma cafeteria, com o objetivo de compreender o comportamento de consumo, identificar padrões relevantes e extrair insights que possam apoiar decisões estratégicas nas áreas de marketing, precificação e gestão de produtos.

Este foi um dos meus primeiros projetos autorais em Ciência de Dados, desenvolvido para praticar análise exploratória, visualização e estruturação de um fluxo analítico completo em Python.

---

## Objetivos

A análise busca responder a questões como:

- Quais produtos têm maior volume de vendas e maior faturamento?
- Como as vendas variam ao longo do tempo (diário, semanal, mensal)?
- Há padrões de sazonalidade ou recorrência?
- Como o preço médio se comporta entre diferentes tipos de café?
- Existem dias da semana com melhor ou pior desempenho?
- Que oportunidades estratégicas podem ser extraídas desses padrões?

---

## Sobre o Dataset

O conjunto de dados contém registros de vendas entre março/2024 e março/2025.  
Principais colunas:

- `date` – data da venda  
- `datetime` – horário da venda  
- `cash_type` – forma de pagamento  
- `money` – valor da transação  
- `coffee_name` – tipo de café vendido  

A estrutura permite análises tanto por produto quanto temporais.

---

## Preparação dos Dados

As principais etapas de preparação foram:

1. Conversão das colunas de datas.  
2. Verificação e tratamento de valores ausentes.  
3. Criação de variáveis auxiliares:  
   - dia da semana  
   - mês  

---

## Análises Realizadas

### 1. Análise por Produto
- Volume de vendas por tipo de café  
- Faturamento por produto  
- Preço médio  
- Comparação entre volume e ticket médio  

Essas análises permitem identificar:
- produtos mais populares  
- itens que mais contribuem para o faturamento  
- bebidas de maior ticket médio que podem receber mais destaque  

---

### 2. Análise Temporal
Foram avaliadas variações por:
- dia  
- dia da semana  
- mês  

Algumas observações relevantes:
- tendência de crescimento nos meses finais  
- pico de vendas em outubro/2024  
- maior movimento em dias úteis  
- menor demanda aos domingos  

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
