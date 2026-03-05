# Análise de Vendas de Cafeteria: Estratégia de Receita e Padrões de Demanda
*Análise exploratória de vendas para entender desempenho de produtos, padrões de demanda e oportunidades de melhorar a receita.*

**Dataset:** 3.636 transações (março de 2024 – março de 2025)  
**Técnicas:** análise exploratória de dados, análise temporal e análise de faturamento  
**Resultado principal:** identificação dos principais produtos geradores de receita e padrões de demanda ao longo do ano

---

## Contexto de Negócio

Cafeterias operam em um ambiente dinâmico, onde a demanda varia ao longo dos dias e das estações do ano. Pequenas melhorias no posicionamento de produtos, promoções e planejamento operacional podem ter impacto relevante na receita.

Entender **quais produtos geram mais faturamento**, **quando a demanda aumenta ou diminui**, e **onde existem oportunidades operacionais** permite tomar decisões melhores sobre preços, marketing e planejamento.

Mesmo utilizando um dataset público, o projeto foi estruturado como um cenário real de análise para apoiar decisões de negócio.

---

## Dataset

Fonte:  
https://www.kaggle.com/datasets/ihelon/coffee-sales

Características do dataset:

• **3.636 transações de vendas**  
• Período: **março de 2024 a março de 2025**  
• Dados no nível de transação  

Principais variáveis:

• `date` — data da venda  
• `datetime` — data e hora da transação  
• `cash_type` — forma de pagamento  
• `money` — valor da venda  
• `coffee_name` — produto vendido  

Um ponto interessante é que **97,5% das transações foram feitas com cartão**, indicando um perfil de cliente majoritariamente digital.

---

## Problema de Negócio

Como os dados de vendas podem ser analisados para identificar **produtos mais relevantes, padrões de demanda e oportunidades de melhoria de receita** em uma cafeteria?

---

## Objetivos

- Identificar os produtos que geram **maior volume de vendas e maior faturamento**
- Realizar uma **análise exploratória estruturada**
- Analisar **padrões temporais** de demanda
- Comparar produtos de **alto volume versus alto faturamento**
- Traduzir resultados analíticos em **insights de negócio**

---

## Metodologia

1. **Limpeza e preparação dos dados**  
Conversão de datas, verificação de valores ausentes e criação de variáveis temporais.

2. **Análise exploratória**  
Investigação de padrões de vendas e faturamento.

3. **Análise temporal**  
Estudo de padrões diários e mensais para identificar sazonalidade.

4. **Análise de faturamento**  
Comparação entre popularidade de produtos e geração de receita.

5. **Geração de insights**  
Tradução dos resultados analíticos em recomendações de negócio.

---

## Ferramentas Utilizadas

• Python  
• Pandas  
• NumPy  
• Matplotlib  
• Seaborn  
• Google Colab  

---

## Principais Resultados da Análise

### Vendas por Produto

![Vendas por tipo de café](img/plot1_Vendas%20por%20tipo%20de%20café.png)

**Figura:** volume de vendas por tipo de café.

Produtos mais vendidos:

• Americano with Milk  
• Latte  
• Americano  

---

### Faturamento por Produto

![Faturamento por tipo de café](img/plot2_Faturamento%20por%20Tipo%20de%20Café.png)

**Figura:** faturamento total por produto.

Produtos que mais geram receita:

• Latte  
• Americano with Milk  
• Cappuccino  

---

### Padrões Mensais de Receita

![Faturamento mensal](img/plot9_faturamento%20mensal.png)

**Figura:** evolução mensal do faturamento.

A análise mensal mostra variações ao longo do ano, indicando períodos de maior e menor demanda.

---

## Principais Insights

• Americano with Milk e Latte representam a base da demanda recorrente.  
• Latte aparece como o principal gerador de receita.  
• Espresso funciona como produto de entrada com menor preço.  
• Existem variações de demanda ao longo do ano que podem orientar promoções.

---

## Impacto de Negócio

Os resultados podem apoiar decisões como:

• Estratégia de posicionamento de produtos  
• Planejamento de estoque e equipe  
• Criação de campanhas sazonais  
• Monitoramento de desempenho de vendas

---

## Próximos Passos

Possíveis evoluções do projeto:

• Incluir dados de custo para análise de margem  
• Criar um modelo de previsão de vendas  
• Automatizar relatórios de desempenho  
• Construir um dashboard de monitoramento

---

## Estrutura do Repositório
```
.
├── data
├── notebooks
├── images
├── requirements.txt
└── README.md
```


---

## Conclusão

Este projeto mostra como uma análise exploratória estruturada pode transformar dados de vendas em insights úteis para decisões de negócio.

Além da análise técnica, o foco do projeto foi gerar **insights claros e aplicáveis para melhorar estratégia de receita e planejamento operacional.**




