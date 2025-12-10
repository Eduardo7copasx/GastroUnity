# Problema de negócio 

A GastroUnity é uma empresa de tecnologia especializada em soluções para o setor de alimentação. Seu principal produto é um aplicativo inovador que conecta restaurantes a consumidores, facilitando a descoberta de estabelecimentos, tipos de culinária e a localização em diferentes países e cidades.

O aplicativo gera uma grande quantidade de dados estratégicos — como endereço, tipo de culinária servida, se possui reservas, se faz entregas e também uma nota de avaliação dos serviços e produtos do restaurante, dentre outras informações. No entanto, apesar do crescimento acelerado da base de restaurantes, o CEO ainda não possui visibilidade clara sobre os principais KPIs de expansão e desempenho da empresa.

Diante desse cenário, você foi contratado como Cientista de Dados para desenvolver soluções baseadas em dados que apoiem a tomada de decisão. Antes de avançar para a criação de modelos preditivos, a necessidade mais urgente é consolidar os KPIs estratégicos em uma única ferramenta, oferecendo ao CEO uma visão simples, objetiva e centralizada do desempenho do negócio.

A GastroUnity opera no modelo de negócio Marketplace, atuando como intermediadora entre restaurantes e consumidores. Para acompanhar o avanço da plataforma e orientar decisões de crescimento, o CEO deseja monitorar as seguintes métricas-chave:

## Geral

1. Quantos restaurantes únicos estão registrados?
2. Quantos países únicos estão registrados?
3. Quantas cidades únicas estão registradas?
4. Qual o total de avaliações feitas?
5. Qual o total de tipos de culinária registrados?

   
## Pais

1. Qual o nome do país que possui mais cidades registradas?
2. Qual o nome do país que possui mais restaurantes registrados?
3. Qual o nome do país que possui mais restaurantes com o nível de preço igual a 4
registrados?
4. Qual o nome do país que possui a maior quantidade de tipos de culinária
distintos?
5. Qual o nome do país que possui a maior quantidade de avaliações feitas?
6. Qual o nome do país que possui a maior quantidade de restaurantes que fazem
entrega?
7. Qual o nome do país que possui a maior quantidade de restaurantes que aceitam
reservas?
8. Qual o nome do país que possui, na média, a maior quantidade de avaliações
registrada?
9. Qual o nome do país que possui, na média, a maior nota média registrada?
10. Qual o nome do país que possui, na média, a menor nota média registrada?
11. Qual a média de preço de um prato para dois por país?

    
## Cidade

1. Qual o nome da cidade que possui mais restaurantes registrados?
2. Qual o nome da cidade que possui mais restaurantes com nota média acima de
4?
3. Qual o nome da cidade que possui mais restaurantes com nota média abaixo de
2.5?
4. Qual o nome da cidade que possui o maior valor médio de um prato para dois?
5. Qual o nome da cidade que possui a maior quantidade de tipos de culinária
distintas?
6. Qual o nome da cidade que possui a maior quantidade de restaurantes que fazem
reservas?
7. Qual o nome da cidade que possui a maior quantidade de restaurantes que fazem
entregas?
8. Qual o nome da cidade que possui a maior quantidade de restaurantes que
aceitam pedidos online?


## Restaurantes

1. Qual o nome do restaurante que possui a maior quantidade de avaliações?
2. Qual o nome do restaurante com a maior nota média?
3. Qual o nome do restaurante que possui o maior valor de uma prato para duas
pessoas?
4. Qual o nome do restaurante de tipo de culinária brasileira que possui a menor
média de avaliação?
5. Qual o nome do restaurante de tipo de culinária brasileira, e que é do Brasil, que
possui a maior média de avaliação?
6. Os restaurantes que aceitam pedido online são também, na média, os
restaurantes que mais possuem avaliações registradas?
7. Os restaurantes que fazem reservas são também, na média, os restaurantes que
possuem o maior valor médio de um prato para duas pessoas?
8. Os restaurantes do tipo de culinária japonesa dos Estados Unidos da América
possuem um valor médio de prato para duas pessoas maior que as churrascarias
americanas (BBQ)?


## Tipos de Culinária
1. Dos restaurantes que possuem o tipo de culinária italiana, qual o nome do
restaurante com a maior média de avaliação?
2. Dos restaurantes que possuem o tipo de culinária italiana, qual o nome do
restaurante com a menor média de avaliação?
3. Dos restaurantes que possuem o tipo de culinária americana, qual o nome do
restaurante com a maior média de avaliação?
4. Dos restaurantes que possuem o tipo de culinária americana, qual o nome do
restaurante com a menor média de avaliação?
5. Dos restaurantes que possuem o tipo de culinária árabe, qual o nome do
restaurante com a maior média de avaliação?
6. Dos restaurantes que possuem o tipo de culinária árabe, qual o nome do
restaurante com a menor média de avaliação?
7. Dos restaurantes que possuem o tipo de culinária japonesa, qual o nome do
restaurante com a maior média de avaliação?
8. Dos restaurantes que possuem o tipo de culinária japonesa, qual o nome do
restaurante com a menor média de avaliação?
9. Dos restaurantes que possuem o tipo de culinária caseira, qual o nome do
restaurante com a maior média de avaliação?
10. Dos restaurantes que possuem o tipo de culinária caseira, qual o nome do
restaurante com a menor média de avaliação?
11. Qual o tipo de culinária que possui o maior valor médio de um prato para duas
pessoas?
12. Qual o tipo de culinária que possui a maior nota média?
13. Qual o tipo de culinária que possui mais restaurantes que aceitam pedidos
online e fazem entregas?

# Premissas assumidas para a análise

1. Marketplace foi o modelo de negócio assumido.
2. Os 3 principais visões do negócio foram: Visão país, visão cidade e visão culinária.

# Estratégia da solução

O painel estratégico foi desenvolvido utilizando as métricas que
refletem as 3 principais visões do modelo de negócio da empresa:

1. Visão das métricas dos paises
2. Visão das métricas das cidades
3. Visão das métricas das culinárias

Cada visão é representada pelo seguinte conjunto de métricas.

## 1. Visão das métricas dos paises

a. Restaurantes registrados por país.

b. Cidades registradas por país.

c. Média de avaliações feitas por país.

d. Média de preço de um prato para duas pessoas por país.

## 2. Visão das métricas das cidades

a. Top 10 cidades com mais restaurantes na base de dados.

b. Top 7 cidades com restaurantes com média acima de 4.

c. Top 7 cidades com restaurantes com média abaixo de 2.5.

d. Top 15 cidades com mais restaurantes de tipos culinários distintos.

## 3. Visão do crescimento dos entregadores

a. Melhores restaurantes dos principais tipos culinários.

b. Top restaurantes.

c. Top piores tipos de culinária.

d. Top melhores tipos de culinária.

# Top 3 Insights de dados

• Indonésia e Austrália estão entre os países com os maiores custos médios para uma refeição para duas pessoas, indicando um posicionamento de mercado voltado ao público de maior poder aquisitivo ou a predominância de restaurantes com ticket médio mais elevado.

• As cidades que concentram restaurantes com avaliações acima de 4,0 estão majoritariamente localizadas em países desenvolvidos, o que sugere padrões de qualidade mais elevados, maior competitividade e consumidores mais exigentes nesses mercados.

• Os restaurantes com as melhores avaliações também apresentam mais de 200 votos, demonstrando que classificações altas estão diretamente associadas a maior engajamento dos usuários e a uma base de avaliações mais robusta e confiável.

# O produto final do projeto

Painel online, hospedado em um Cloud e disponível para acesso
em qualquer dispositivo conectado à internet.

O painel pode ser acessado através desse link:https://gastrounity-cds.streamlit.app/

# Conclusão

O objetivo desse projeto é criar um conjunto de gráficos e/ou
tabelas que exibam essas métricas da melhor forma possível para
o CEO. 

# Próximo passos

1. Reduzir o número de métricas.
2. Criar novos filtros.
3. Adicionar novas visões de negócio.
