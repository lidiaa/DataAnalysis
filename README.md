# DataAnalysis


# Análise de vendas
Tabela de vendas inspirada no workshop do Prof. Italo Diego Teotônio.
Disponível em: <https://www.youtube.com/watch?v=f3NZJCaF8Bw>. Acesso em 16 mar. 2024


## Objetivos:
1. Definir o total faturado por cada vendedor dentro do ano
2. Definir a receita da empresa por mês
3. Definir cada cliente gastou dentro do ano
4. Definir a receita por cliente dentro do ano
5. Quantidade de produtos vendidos no ano
6. Quantidade de pedidos recebidos no ano

## Correções na tabela de dados:
Alterações do tipo, conversão para Camel Case, padronização das sigla dos Estados

## Visualizações (gráficos) utilizadas:
1. Gráfico de colunas clusterizado (adequado para a formação do ranking dos vendedores)
- eixo x: nome do representante (vendedor)
- eixo y: valor total das vendas

2. Gráfico de área, que exibe de forma sistemática os valores mensais
- eixo x: mês de data pedido
- eixo y: valor total das vendas


3. Cartão para a informação obter destaque
- Campo: soma do valor total das vendas

4. Gráfico de barras clusterizado (adequado para a formação do ranking dos melhores clientes)
- eixo x: valor total das vendas
- eixo y: nome do cliente


5. Cartão para a informação ter destaque
- Campo: soma da quantidade vendida


5. Cartão para a informação ter destaque
- Campo: contagem do id pedido

## Insights obtidos através da análise dos dados:
- O Estado do Rio de Janeiro é o que possui mais produtos vendidos (38.314 unidades) e também o de maior faturamento (R$ 47.85 milhões) em 724 pedidos, obtendo um ticket médio de R$ 66.091,16 por pedido
- O mês de julho foi o de maior faturamento no ano de 2020, sendo que os clientes que mais compraram no referido mês foram Ricardo Eletro e Kabum
- O Estado da Paraíba obteve o pior desempenho em produtos vendidos, pedidos e faturamento anual
- O colaborador Paulo Ferreira se destaca para as vendas ao cliente Magazine Luiza, Tais Fernandes para a Casas Bahia e Lucas Souza para a Shoptime
- A Shoptime é uma cliente estável, se mantendo entre compras de 1 a 2 milhões durante o ano
- O decreto de lockdown que se deu em 20 de março de 2020, bem como a imprevisibilidade do cenário da economia desde fevereiro podem ter sido responsáveis pela queda de quase 2 milhões do faturamento nos referidos meses. Em abril, com muitas empresas e funcionários se adaptando à nova realidade do trabalho remoto, as vendas foram novamente subindo, com pico em julho e dezembro e uma queda atípica em outubro
- Aproximadamente 80% do faturamento (R$ 142.216.000) foi obtido com as vendas na região Sudeste (R$ 140.380.000)

|Estado| Faturamento|
|-----| -----------|
|RJ |R$ 47.850.000 |
|ES |R$ 33.070.000 |
|MG | R$ 32.090.000 |
|SP | R$ 27.370.000 |


# ---------------------------------------------


# Campeonato Brasileiro 2023

Relatório de jogos do Campeonato Brasileiro de Futebol do ano de 2023, Série A, baseado na tabela de dados de A. Duque, disponível em: <https://www.kaggle.com/datasets/adaoduque/campeonato-brasileiro-de-futebol/data>. Acesso em 16 mar. 2024.

## Objetivos
1. Montar um quadro geral de análise do campeonato
2. Analisar as formações mais utilizadas pelas equipes
3. Verificar quais foram os estádios mais utilizados
4. Obter uma lista com quantos jogos cada time venceu


## Correções na tabela de dados:
Criação de nova coluna total_gols_partida, com a soma do mandante_Placar e visitante_Placar, renomear a coluna "rodata" para "rodada"


## Visualizações (gráficos) utilizadas:
1. Cartões para obter dados gerais do campeonato, como o número de jogos, quantidade de gols, média de gols por partida e total de jogos com resultado empate

2. Gráficos de pizza com filtro dos top 5 itens para análise das principais formações utilizadas pelos times enquanto mandantes ou visitantes
- contagem de formação

3. Gráfico de barras clusterizado para obter a contagem dos vencedores
- eixo x: contagem de vencedor
- eixo y: vencedor

4. Treemap para visualização dos estádios com mais partidas realizadas 
- valores: contagem de arena


## Insights obtidos através da análise dos dados:
- Tanto os mandantes quanto os visitantes costumam utilizar a mesma estratégia de formação (4-2-3-1; 4-3-3, 4-1-4-1, 4-4-2, 3-4-2-1);
- Cerca de 25% dos jogos da campeonato terminaram em empate (98 jogos);
Há forte tendência de que o time que jogue em seu estádio saia vencedor;
- Mineirão foi o estádio em que mais ocorreram empates (11);
- O Palmeiras, vencedor do campeonato, ganhou 20 jogos, enquanto o Grêmio, que ficou em segundo lugar, ganhou 21 partidas.


