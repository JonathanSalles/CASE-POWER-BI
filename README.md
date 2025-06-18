# CASE POWER-BI
Preveja os resultados de um e-commerce utilizando o Power BI

https://dncgroupbr.notion.site/Desafio-Preveja-os-resultados-de-um-e-commerce-utilizando-o-Power-BI-bbe09a05b449498bb645208799cda5ea

# Desafio: Preveja os resultados de um e-commerce utilizando o Power BI

## 🚀 Desafio

Preveja os resultados de um e-commerce utilizando o Power BI. Você irá aplicar os seus conhecimentos de Excel e Power BI para construir um painel gerencial de um e-commerce que seja capaz de direcionar a uma análise de negócio para que a empresa defina as estratégias com o objetivo de aumentar as suas vendas. Também deverá estabelecer recomendações sobre como a empresa pode melhorar seus resultados.

## Contexto

Neste desafio, você deverá construir um painel gerencial para um e-commerce que almeja estudar as suas vendas e assim, traçar a melhor estratégia para alavancar seus resultados.

Você receberá duas bases de dados, uma com dados das vendas e outra com informações dos clientes. Com isso, crie duas páginas para que os analistas possam visualizar as métricas.

Crie as determinadas métricas: Quantidade total e valor total de vendas, Contagem e valor total de vendas por data, quantidade e valor total por categoria e crie os filtros necessários para fornecer ao usuário a melhor experiência. Lembrem-se do storytelling e de um bom layout para ser atrativo.

### Detalhamento das tabelas:

| Coluna | Descrição | Base |
| --- | --- | --- |
| idcompra | numero de identificação da compra | base compra |
| idcanalvenda | Canal de venda | base compra |
| bandeira | Qual foi a bandeira que a compra foi realizada | base compra |
| Data | Data da compra | base compra |
| Preço | Preço da compra | base compra |
| Preço_com_frete | Preço da compra + frete | base compra |
| Nome_Departamento | Departamento do produto | base compra |
| estado | Estado da compra | base compra |
| cliente_Log | Identificação do cliente | base compra |
| cliente_Log | Identificação do cliente | Base cliente |
| Idade | Idade do cliente | Base cliente |
| uf_nascimento | Cidade de nascimento | Base cliente |
| Renda | renda do cliente | Base cliente |

### Como começar?

Com base no contexto fornecido, é necessário criar dashboards para permitir que a equipe de negócios desenvolva planos de ação com o objetivo de aumentar o número de usuários cadastrados e impulsionar o crescimento da empresa.

1.  Importe as duas bases para o Power BI.
2.  Crie uma coluna na base cliente de faixa de rendas, clusterizando entre os seguintes valores:
    -   Até 10000
    -   Até 7500
    -   Até 5000
    -   Até 2500
    -   Até 1750
3.  Crie 2 páginas: `Visão do clientes` e `Visão Compra`.

## 🎯 Etapas de Desenvolvimento

Para te ajudar nesse processo, o PO do projeto pediu alguns gráficos para ter visibilidade do processo:

### Etapa 01) Tipo de gráfico: Cartões

-   Crie um card de quantidade de vendas
-   Crie um card de valor total de vendas sem frete ($)
-   Crie um card de valor total de vendas com frete ($)
-   Crie um card de quantidade de clientes
-   Crie um card de média de renda dos clientes

### Etapa 02) Tipo de gráfico: Gráfico de linhas

-   Contagem de vendas por mês
-   Valor total de vendas por mês

### Etapa 03) Tipo de gráfico: Gráfico de Barras

-   Quantidade de vendas por categoria
-   Valor total de vendas por categoria
-   Distribuição de idades dos clientes
-   Distribuição de renda dos clientes

### Etapa 04) Filtro

-   Bandeira
-   Estado
-   Canal de venda
-   Departamento
-   Idade
-   Faixa de renda
-   Estado de nascimento

## 📝 Critérios de Avaliação

| Critérios | Atendeu às Especificações | Pontos |
| --- | --- | --- |
| Tipo de gráfico: Cartão | Elabore 5 gráficos tipo cartão utilizando as simbologias de moeda para representar indicadores financeiros | 20 |
| Tipo de gráfico: Linhas | Crie 2 gráficos de linhas, onde o eixo x deve ser uma série temporal (datas), representando tendências ao longo do tempo | 30 |
| Tipo de gráfico: Barras | Crie 4 gráficos de barras: 2 gráficos comparando vendas por categoria (um em quantidade de vendas e outro em valor de vendas), 1 histograma de idades dos clientes, e 1 gráfico de barras para a distribuição de rendas dos clientes | 30 |
| Filtro | Crie filtros interativos para as seguintes categorias: bandeira, estado, canal de venda, departamento, idade, faixa de renda, e estado de nascimento | 20 |
