# Alura Challenge BI
O desafio consiste em desenvolver dashboards de logística, marketing e financeiro, utilizando conceitos de BI, do básico ao avançado, e criar um portfólio na área. Tudo isso durante as quatro semanas propostas no desafio.

Semana 1: Logística

Semana 2: Marketing

Semana 3 e 4: Financeiro

## Semana 1: Alura Log 🚚

A gerente da área de logística da Alura Log, está enfrentando algumas mudanças em sua área por conta do aumento da demanda dos serviços de logística no período da pandemia. Ela quer manter a qualidade de seu serviço, mas para isso precisa acompanhar constantemente as métricas do seu departamento para tomar as melhores decisões. Quando nos contou isso, analisamos que para auxiliar nesse desafio precisaremos fazer um dashboard para logística. Para isso, vamos visualizar algumas métricas muito importantes para a área.

Indicadores solicitados:

✔️ Visualizar quantas entregas foram feitas no prazo

✔️ Visualizar quantas entregas foram feitas atrasadas

✔️ Mostrar o número de veículos disponíveis

✔️ Calcular o S2D - Ship to door - expedição até a entrega, medido em dias

✔️ Visualizar o nível médio de estoque por ano

✔️ Mostrar o índice de ocorrências por estado.

### Etapa 1: ETL
As fontes de dados são 4 planilhas em .csv extraídas para o Power BI através do Power Query. As principais transformações necessárias foram divisão de coluna, substituição de valor, tratamento de datas (formato EUA) e join. Nessa etapa, também são revisados/criados os relacionamentos entre as tabelas carregadas.

### Etapa 2: criação das medidas (indicadores)

### Etapa 3: montagem do dashboard
O esquema de cores foi utilizado com o intuito de facilitar a visualização dos dados, tornando-o mais acessível.

Dashboard:
![image](https://user-images.githubusercontent.com/78048771/135943028-0a77609c-4b83-4ec5-9204-86b4731b51db.png)


✔️ Plus! Adicionado o indicador da quantidade de veículos ocupados

✔️ Plus! Adicionado o ranking dos maiores preços de vendas das 5 maiores categorias


## Semana 2: Alura Shop 🛒

Agora a Alura Shop investiu em publicidade para se destacar no mercado, e a gerência da empresa tem dúvidas se o retorno dessa propaganda surtiu efeito. A nossa missão é apoiar a gerência em suas tomadas de decisão, e elucidar as dúvidas. Para isso desenvolveremos um dashboard estratégico de marketing com o objetivo de monitorar uma campanha de publicidade paga durante o mês de julho de 2021. Apresentaremos indicadores relevantes para a validação estratégica do negócio.

Indicadores solicitados:

✔️ Calcular o total de compras

✔️ Calcular o total de valor convertido em compras

✔️ Mostrar o total do valor investido na campanha

✔️ Calcular o custo por clique

✔️ Exibir a jornada de compra

✔️ Calcular a taxa de conversão

✔️ Mostrar o ticket médio por dispositivo

✔️ Mostrar Retorno do investimento em publicidade (ROAS) por idade e gênero

✔️ Calcular o valor convertido em compras por dia

### Etapa 1: ETL
As fontes de dados são 2 arquivos em .json extraídos para o Power BI através do Power Query sem grandes manupilações nas bases de dados

### Etapa 2: criação das medidas (indicadores)

### Etapa 3: montagem do dashboard
O esquema de cores foi utilizado com o intuito de facilitar a visualização dos dados, tornando-o mais acessível.

Dashboard:
![image](https://user-images.githubusercontent.com/78048771/135943106-83af7f04-e042-4eae-805a-d3476d99da97.png)


## Semana 3: Alura Store

Desenvolveremos um dashboard tático da área financeira de uma empresa, no qual vamos criar duas páginas, sendo uma delas exibindo um overview de toda a área financeira e a outra página realizando uma análise de cenários.
Teremos duas etiquetas indicando o que precisaremos pensar, sendo elas:
1 - Overview financeiro.
2 - Análise de cenário.

Indicadores solicitados:

✔️ Calcular a receita.

✔️ Calcular o lucro.

✔️ Escolher o ano a ser analisado

✔️ Calcular a despesa

✔️ Escolher as melhores métricas para auxiliar na tomada de decisão

### Etapa 1: ETL
As fontes de dados 3 bases dentro um banco de dados no MySQL e a principal tranformação foi ajustar os valores com as casas decimais.

### Etapa 2: criação das medidas (indicadores)

### Etapa 3: montagem do dashboard
O esquema de cores foi utilizado com o intuito de facilitar a visualização dos dados, tornando-o mais acessível.

Dashboard:
![image](https://user-images.githubusercontent.com/78048771/135943202-8495dabc-9874-40f6-81df-937d1a9ba7ba.png)


## Análise de cenários 🔥
Qual é o impacto se ocorrer uma variação no custo de produção? E se os impostos mudarem? E se minha receita aumentar? Essas foram algumas perguntas que respondemos para nosso cliente através do dashboard abaixo.

### Etapa 1: criação dos parâmetros

### Etapa 2: montagem do dashboard
O esquema de cores foi utilizado com o intuito de facilitar a visualização dos dados, tornando-o mais acessível.

Dashboard:
![image](https://user-images.githubusercontent.com/78048771/135943342-b1f3c974-027b-4fe5-8d0a-3456a7b1ddcd.png)


