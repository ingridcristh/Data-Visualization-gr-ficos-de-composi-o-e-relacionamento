# Data Visualization: Gráficos de Composição e Relacionamento

## Descrição do Projeto

Neste projeto, trabalhamos com a base de dados dos PIBs (Produto Interno Bruto) dos estados brasileiros no período de 2002 a 2020. O objetivo é analisar este conjunto de dados para compreender a composição do PIB em relação aos estados do Brasil durante esse período. Os dados descrevem os valores do PIB e os valores agregados anualmente por setores como agropecuária, indústria, serviços e outros.

## Objetivos

O projeto tem como intuito colocar em prática diversas técnicas de análise e visualização de dados, incluindo:

- Comparação de dados
- Agrupamento de dados
- Séries temporais
- Distribuição de dados
- Exploração de padrões nos dados

## Questionamentos

As principais perguntas que este projeto busca responder são:

1. **Como está disposto o PIB nos estados brasileiros no ano de 2020?** 
   - É possível notar os estados com maior e menor participação no PIB nacional?

2. **Houve uma significativa mudança na distribuição do PIB por região comparando os valores de 2002 e 2020?**

3. **Qual a participação do estado de Minas Gerais no PIB de todo o Brasil no ano de 2020?**

4. **Como está distribuído o PIB do estado da Bahia em 2020, separado por impostos líquidos e os valores adicionados brutos dos bens e serviços produzidos?**

5. **Qual a evolução anual do PIB do estado do Rio de Janeiro entre os anos de 2010 a 2020?**

6. **Como está distribuído o PIB nos 3 últimos quinquênios (lustros) dos dados (2010, 2015, 2020) na Região Sul do Brasil, dividido pelos estados (Paraná, Santa Catarina e Rio Grande do Sul)?**

7. **Como estão distribuídos, em porcentagem, os valores adicionados de bens e serviços descritos na base de dados em relação a cada região no ano de 2020?**

8. **Na agropecuária, como estão distribuídos seus valores adicionados por região dentro do período da base dos dados (2002 - 2020)?**

## Composição da Tabela

A base de dados é composta pelas seguintes tabelas e colunas:

- **ano:** ano de representação dos dados
- **sigla_uf:** sigla do Estado representada na base de dados
- **regiao:** região do Estado
- **pib:** valor do PIB do Estado
- **impostos_liquidos:** impostos líquidos do Estado
- **va:** valor adicionado bruto a preços correntes das atividades econômicas
- **va_agropecuaria:** valor adicionado bruto a preços correntes da agropecuária
- **va_industria:** valor adicionado bruto a preços correntes da indústria
- **va_servicos:** valor adicionado bruto a preços correntes dos serviços, exceto administração, defesa, educação e saúde públicas e seguridade social
- **va_adespss:** valor adicionado bruto a preços correntes da administração, defesa, educação e saúde públicas e seguridade social

## Gráficos Utilizados

Para a visualização dos dados, utilizamos diversos tipos de gráficos, incluindo:

1. Gráfico de pizza
2. Gráfico de rosca
3. Gráfico de árvore (Treemap)
4. Gráfico de cascata simples
5. Colunas agrupadas x empilhadas
6. Gráfico de barras empilhadas
7. Gráfico de áreas
8. Gráfico de inclinação

## Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando a linguagem de programação Python e as seguintes bibliotecas:

- **Pandas:** para manipulação e análise de dados.
- **Seaborn:** para visualização de dados estatísticos.
- **Matplotlib:** para criação de gráficos estáticos, animados e interativos.
- **Plotly.graph_objects:** para criação de gráficos interativos.

## Conclusão

Este projeto permite uma análise detalhada da composição e evolução do PIB dos estados brasileiros, utilizando diversas técnicas de visualização para facilitar a compreensão dos dados e responder às perguntas propostas. Através das visualizações geradas, é possível identificar padrões, tendências e variações na economia dos estados e regiões do Brasil ao longo do período analisado.
