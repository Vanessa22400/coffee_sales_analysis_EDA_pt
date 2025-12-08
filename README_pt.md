# Coffee Sales Analysis: Exploratory Data Analysis (EDA)

Este é um projeto de análise de vendas de uma cafeteria, com foco em entender o comportamento de consumo de diferentes tipos de café, identificar padrões relevantes e explorar insights que possam apoiar decisões estratégicas de marketing e vendas.

Foi um dos meus primeiros projetos autorais em Data Science, criado para praticar análise exploratória, visualização de dados e organização de um fluxo analítico completo.

### Objetivos
Ao longo da análise, busco responder perguntas como:

- Quais são os cafés mais vendidos em termos de quantidade e faturamento?
- Como as vendas variam ao longo do tempo (diariamente, mensalmente)?
- Existe padrão de sazonalidade nas vendas?
- Como o preço médio varia entre os diferentes tipos de café?
- Há dias da semana melhores para vendas?
- Quais oportunidades estratégicas podem ser extraídas desses padrões?


### Sobre o Dataset
O dataset contém registros de vendas entre **março/2024 e março/2025**.
As principais colunas são:

- `date`: data da venda
- `datetime`: hora da venda
- `cash_type`: forma de pagamento 
- `money`: valor da venda
- `coffee_name`: tipo de café vendido

Essas informações permitem análises tanto por **produto**, quanto **temporal** (dia, semana, mês).

### Preparação do Dataset

As etapas de preparação envolveram:
1. Conversão das colunas de datas para formato datetime.
2. Verificação de valores ausentes.
3. Criação de colunas auxiliares:
* dia da semana
* mês

### Análises Realizadas

**1) Análise de Produtos**

* Quantidade de vendas por tipo de café
* Faturamento por produto
* Preço médio por café
* Comparação entre volume × ticket médio

Essa etapa permitiu identificar:
* produtos mais populares
* produtos com maior impacto no faturamento
* itens com ticket médio alto que merecem destaque no mix


**2) Análise Temporal**

Foram avaliados padrões ao longo de:
* dias
* dias da semana
* meses

Alguns achados importantes:

* tendência de crescimento nos meses finais do período
* pico acentuado em outubro/2024
* dias úteis apresentam maior movimento
* domingos têm menor volume de vendas

**3) Insights de Negócio**

A análise aponta oportunidades como:
* planejar campanhas de marketing em torno de maio e outubro, aproveitando o histórico de picos de vendas.
* destacar o *Espresso* em promoções de baixo custo para atrair novos clientes e incentivá-los a experimentar outras bebidas de maior ticket médio.  
* oferecer descontos ou combos às terças-feiras (melhor dia de vendas) e ações especiais para atrair público aos domingos, quando o movimento é menor.  
* automatizar relatórios mensais para monitorar vendas e faturamento e ajustar rapidamente as ações de marketing.


### Próximos Passos

Para evoluir o projeto:
* integrar dados de custo para calcular margens de lucro por produto
* explorar perfis de cliente usando a coluna `card`
* construir um modelo simples de **previsão de vendas**
* automatizar relatórios mensais

### Ferramentas Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
