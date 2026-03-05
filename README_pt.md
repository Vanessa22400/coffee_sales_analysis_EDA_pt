# Análise de Vendas de Cafeteria: Estratégia de Receita e Padrões de Demanda (Mar/2024 – Mar/2025)

Este projeto apresenta uma análise exploratória de dados de vendas de uma cafeteria ao longo de aproximadamente um ano.

O objetivo é entender **quais produtos geram mais receita, como a demanda varia ao longo do tempo e quais oportunidades estratégicas podem melhorar o desempenho do negócio**.

---

## Dataset

Dataset público disponível no Kaggle:  
https://www.kaggle.com/datasets/ihelon/coffee-sales

O conjunto de dados contém **3.636 transações entre março de 2024 e março de 2025**, com as seguintes colunas principais:

- `date` – data da venda  
- `datetime` – data e hora da venda  
- `cash_type` – forma de pagamento  
- `money` – valor da transação  
- `coffee_name` – tipo de café vendido  

---

## Objetivos

A análise busca responder perguntas como:

- Quais produtos geram mais faturamento?
- Quais cafés são mais vendidos?
- Existem padrões de demanda ao longo do tempo?
- Quais períodos são mais fortes ou mais fracos?
- Que ações poderiam melhorar o desempenho do negócio?

---

## Preparação dos Dados

As principais etapas de preparação incluíram:

- Conversão das colunas de data para formato datetime
- Criação de variáveis temporais (dia da semana, hora e mês)
- Verificação de valores ausentes

Um insight interessante é que **97,5% das transações foram realizadas com cartão**, indicando um perfil de cliente predominantemente digital.

---

## Principais Visualizações

### Vendas por Produto

![Vendas por tipo de café](img/plot1_Vendas%20por%20tipo%20de%20café.png)

Os cafés mais vendidos foram:

- Americano with Milk (824)
- Latte (782)
- Americano (578)

Esses produtos representam a base de demanda da cafeteria.

---

### Faturamento por Produto

![Faturamento por tipo de café](img/plot2_Faturamento%20por%20Tipo%20de%20Café.png)

Ao analisar o faturamento, observamos que **nem sempre o produto mais vendido é o que mais gera receita**.

Os principais produtos em faturamento foram:

- Latte — 27.866
- Americano with Milk — 25.269
- Cappuccino — 18.034

---

### Evolução das Vendas Diárias

![Vendas diárias](img/plot4_vendas%20diarias.png)

As vendas diárias apresentam bastante variação ao longo do período, com alguns picos bem marcados.

Também é possível perceber uma leve tendência de crescimento no início de 2025.

---

### Faturamento Mensal

![Faturamento mensal](img/plot9_faturamento%20mensal.png)

A análise mensal ajuda a identificar padrões de sazonalidade.

Por exemplo:

- **Maio de 2024** apresentou o maior volume de vendas.
- **Abril de 2024** teve o menor movimento.

Essas informações podem ajudar no planejamento de campanhas e promoções.

---

## Insights de Negócio

A partir da análise, alguns pontos importantes aparecem:

- Latte e Americano with Milk são os principais motores de receita.
- Espresso funciona como um produto de entrada de menor preço.
- Há variações claras de demanda ao longo do ano.
- Alguns períodos podem se beneficiar de campanhas específicas para aumentar o fluxo de clientes.

---

## Próximos Passos

Possíveis evoluções para o projeto:

- Incluir dados de custo para analisar margem de lucro
- Criar um modelo simples de previsão de demanda
- Explorar comportamento de clientes
- Automatizar relatórios mensais

---

## Ferramentas Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Contexto

Este foi o primeiro projeto completo de análise de dados que desenvolvi de forma independente. Escolhi esse tema pelo meu interesse no mercado de cafeterias e também pela minha experiência anterior em vendas, o que me levou a focar a análise em **insights de negócio e estratégia de receita**.
