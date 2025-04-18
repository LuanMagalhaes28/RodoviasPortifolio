# Análise de Acidentes nas Rodovias Brasileiras

Este projeto foi desenvolvido com o objetivo de explorar, por meio da análise de dados e visualizações interativas em Power BI, o cenário dos acidentes registrados nas rodovias federais brasileiras entre os anos de 2022 e 2024.
Utilizei um conjunto robusto de dados públicos para construir um painel que não apenas apresenta números, mas conta uma história sobre segurança viária no Brasil, ajudando a responder perguntas como:
- Quais são as rodovias mais perigosas?
- Qual o perfil das vítimas?
- Quais períodos concentram mais acidentes?<br><br>

## Objetivos do Projeto:
- Investigar a quantidade e gravidade dos acidentes por ano, mês, dia da semana e horário.
- Entender os principais tipos de acidentes e pistas mais perigosas.
- Identificar o perfil das vítimas (por sexo, tipo e estado físico).
- Apontar os trechos rodoviários mais críticos, com destaque para rodovias e estados com maior concentração de ocorrências.
<br>

## FERRAMENTAS UTILIZADAS
- Power BI para construção do dashboard, tooltip e visualizações interativas.<br>
- Criação de medidas personalizadas com DAX, como: BR mais perigosa; Total de vítimas por tipo e estado; Taxas de fatalidade por pista e período<br>
<br>

## CRIAÇÃO DAS MEDIDAS DAX
Um dos pilares deste projeto foi a construção de medidas DAX personalizadas no Power BI, que possibilitaram transformar dados brutos em informações acionáveis e comparáveis. 
Cada medida foi pensada para responder perguntas específicas e permitir a navegação fluida entre diferentes níveis de análise.
<br>

<img align="left" width="300"  src="https://github.com/LuanMagalhaes28/RodoviasPortifolio/blob/main/Prints/Medidas%20DAX.png?raw=true"> Entre as principais medidas desenvolvidas, estão:

- 01 Qtde. Acidentes: Total de acidentes registrados no período.
- 02 Qtde. Feridos: Soma de todas as vítimas feridas.
- 03 Qtde. Mortos: Total de vítimas fatais.
- 04 Mortos %: Percentual de mortos em relação ao total de vítimas.
- 05 Acidentes c/ Mortos: Quantidade de acidentes que resultaram em mortes.
- 09 Total Geral de Mortes: Soma consolidada de todas as mortes nos registros.
<br>
<br>
<br>
<br>
Essas medidas foram fundamentais para permitir filtros dinâmicos por tipo de pista, classificação do acidente, horário, localidade e perfil da vítima, tornando a análise muito mais rica, direcionada e interativa.

<br>

## Dashbooard
Para compreender o cenário de sinistros nas rodovias federais brasileiras, a primeira parte do dashboard foi dedicada a uma análise macro dos dados, explorando padrões de frequência, gravidade, localização e condições das ocorrências entre os anos de 2022 e 2024.
<p align="center"><img src="https://github.com/LuanMagalhaes28/RodoviasPortifolio/blob/main/Prints/Dashboard.png?raw=true" width="800"></p>
Nesta seção, o foco foi em entender o comportamento geral dos acidentes:<br>
- 201 mil acidentes registrados entre 2022 e 2024.<br>
- 15 mil foram fatais, representando 7% do total.<br>
- A rodovia com maior incidência de acidentes foi a BR-101, apontada como a mais perigosa.<br>
- Os meses com mais ocorrências foram dezembro e julho, o que pode estar relacionado a períodos de férias e aumento no fluxo de veículos.<br>
- Sábados e domingos foram os dias com maior número de acidentes, indicando o risco ampliado nos fins de semana.<br>
- O horário com mais ocorrências foi entre 7h e 18h, com destaque para o início da tarde — período de tráfego intenso e maior exposição.<br>
<br>
Classificação dos Acidentes:<br>
- 157 mil com vítimas feridas<br>
- 30 mil sem vítimas<br>
- 15 mil com vítimas fatais<br>
<br>
Tipo de pista:<br>
- Pistas simples lideram com 99 mil acidentes<br>
- Duplas com 83 mil<br>
- Múltiplas com 19 mil<br>
Esses dados apontam que a maioria dos acidentes ocorre em condições de tráfego mais simples, o que levanta hipóteses sobre imprudência, ultrapassagens perigosas e infraestrutura deficiente.

<br>

## Tooltip
Para compreender mais sobre as vítimas, trouxe dados específicos em forma de tooltip.
<p align="center"><img src="https://github.com/LuanMagalhaes28/RodoviasPortifolio/blob/main/Prints/Tooltip.png?raw=true" width="500"></p>
Entre 2022 e 2024, os acidentes resultaram em 711 mil feridos e 80 mil mortes, o que representa uma taxa de 40% de acidentes com vítimas fatais entre os casos com vítimas — um dado alarmante que reforça a gravidade do cenário.
A distribuição por sexo das vítimas mostra uma predominância masculina:<br>
- 71,39% dos envolvidos eram homens, contra 28,61% de mulheres.<br>
Quanto ao estado físico das vítimas, a maioria sofreu lesões leves (128 mil) ou saiu ilesa (126 mil), mas ainda assim houve 47 mil lesões graves e 15 mil óbitos imediatos, revelando a severidade de parte considerável dos acidentes.<br>
Essa análise oferece uma visão mais clara sobre o perfil das vítimas e a gravidade dos sinistros, sendo essencial para pensar estratégias de prevenção mais eficazes e focadas em comportamentos de risco.

### DASHBOARD POWER BI
<a href="https://app.powerbi.com/view?r=eyJrIjoiYTExYzFlMTItZjEyOC00NTg4LTlhNzItZjRlNmY4MDMwNmE2IiwidCI6IjMwYzg4YTkyLTQ0YWUtNGRmNS1hZTYwLTdlMmJkNGIyYjllOSJ9" target="_blank">Clique aqui</a> e acesse o dashboard de forma interativa no Power BI.<br>
Ou se quiser baixar o arquivo em .pbix está disponível no repositório.

