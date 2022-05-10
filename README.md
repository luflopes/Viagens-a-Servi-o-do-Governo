# Despesas com Viagens a Serviço do Governo
### Uma Análise Exploratória

<img src='https://video.fppy8-1.fna.fbcdn.net/v/t1.18169-9/19894597_570661319989282_4606153159333515041_n.png?_nc_cat=111&ccb=1-5&_nc_sid=e3f864&_nc_eui2=AeH4xArczl3OmW1gAqnT694zo2YB4DMgN4CjZgHgMyA3gINcOzo6gh_yuRKfu4x6bbojT2E0QcTy3jzanNhCaZF6&_nc_ohc=l7KBR4ZGce8AX_1LDRy&_nc_ht=video.fppy8-1.fna&oh=00_AT8EopMEoHzPtM3OKFPpJXLWdP8eKupwKaZd0izKTlve4g&oe=629479BE' style='width:1000px; float:left'>

Anualmente, milhões de reais do dinheiro público são destinados ao custeio de viagens a serviço do governo brasileiro.
Viagens a serviço são aquelas realizadas no interesse da Administração do Estado, em território nacional ou estrangeiro. Podem envolver gastos com recursos públicos federais em diárias e/ou passagens. Em 2020 o valor total de gastos com viagens a serviço foi de aproximadamente **740 milhões de reais**. Dado o impacto financeiro que estas despesas geram nas contas públicas, faz-se necessária uma análise mais detalhada sobre este tema.

**Objetivo:** este trabalho tem por objetivo explorar criticamente os dados, gerar insights e propor indicadores de performance que possam direcionar uma gestão mais adequada dos recursos públicos no que diz respeito aos gastos com viagens a serviço da administração do país.
Utilizaremos a linguagem python para esta análise, pois os dados são desconhecidos e esta linguagem nos dá maior flexibilidade para manipular e explorar os dados para que depois possamos tirar conclusões e propor indicadores para o negócio.
___

Durante a análise exploratória dos dados respondemos algumas perguntas que nos direcionaram a proposição dos indicadores de performance. Abaixo, as perguntas e as visualizações. O relatório completo (com o código) pode ser encontrado no aquivo **analise_transportes.ipynb**.

## Qual o valor gasto com viagens do tipo internacional e nacional?

![viagens int e nac](https://user-images.githubusercontent.com/92451100/167731635-014e253f-4529-475a-8140-48c8d56660ff.png)
___
## Qual a proporção entre as quantidades de viagens internacionais e nacionais?

![prop int e nac](https://user-images.githubusercontent.com/92451100/167731747-9064fbfd-44d4-4249-a776-3c556a595957.png)
___

## Os gastos diários foram realizados conforme a determinação da portaria N° 102 de 12 de fevereiro de 2020?

![excederam o limite](https://user-images.githubusercontent.com/92451100/167731952-93cecb50-df6e-4ae6-b0f1-793d3d74da65.png)
___

## Qual o Valor médio gasto com viagens?

Inicialmente, verificamos que os valores de pagamentos não seguem uma distribuição normal e que esta variável possui pontos de máximo e mínimo que podem infunciar fortemente a média. Logo, esta medida não é confiável para representar os dados. Sendo, assim iremos utilizar a mediana para avaliar a proporção de gastos ao longo do ano.

![mediana de gastos](https://user-images.githubusercontent.com/92451100/167732090-bae3f95b-c151-46c6-b3f2-15f2dca44e5d.png)
____

## Qual o Valor total gasto com viagens por órgão superior?

![viagens por orgao](https://user-images.githubusercontent.com/92451100/167732182-84b58744-4e56-4f52-9b4e-1bf15e326b36.png)
Em 2020 o Ministério da Justiça e Segurança gastou aproximadamente 50% do valor total das despesas com viagens a serviço do governo. Nesta época, era de se esperar que os gastos seriam maiores no Ministério da Saúde, pois estávamos iniciando o período pandêmico. Seria interessante analisar mais a fundo este cenário.
___

## Qual a porcentagem e valor gasto das viagens que foram feitas com urgência? 

![Viagens Urgentes](https://user-images.githubusercontent.com/92451100/167732252-b545a085-41f5-4319-9de1-07a806a152d7.png)
___

## Qual a porcentagem de viagens realizadas e não realizadas?

![Viagens nao realizadas](https://user-images.githubusercontent.com/92451100/167732335-ac5d371d-1120-408b-bcf3-ea627539f63a.png)


