# Três fatores para explicar a mortabilidade por covid-19 no Brasil até 11/2020

Este estudo traz insights para tentar explicar as diferentes taxas de mortalidade por covid-19 nas diferentes UFs brasileiras até 11/2020. Foram trabalhados três fatores, descritos a seguir.

## Gastos públicos hospitalares 

Quantidade de leitos, acesso a medicamentos, número de médicos por pacientes, equipamentos para exames, realização de exames, entre outros fatores, influenciam os gastos públicos em saúde.

Considerando as 10 UFs mais impactadas pela pandemia, em mortes por 100 mil habitantes, há 6 cujos gastos hospitalares por habitante figuram entre os 10 mais baixos do Brasil nos últimos 2 anos. Para entender a significância disso, **considere que as chances de 6 UFs quaisquer pertencerem a uma lista congelada de 10 UFs também quaisquer é de menos de 7%**; este estudo está detalhadado no arquivo notebook.

![gastos_hospitalares](/img/gastos.png)

Além dos gastos hospitalares, foram analisados outros 2 possíveis fatores para ajudar a explicar as diferenças nas taxas de óbitos a cada 100 mil habitantes:

## Índice de Gini

Índice de Gini é um indicador socioecônomico que mede a desigualdade de renda da população; eis uma breve explicação a respeito dele:


> índice (ou coeficiente) de Gini: Medida de desigualdade relativa obtida a partir da Curva de Lorenz, que relaciona o percentual acumulado da população em ordem crescente de rendimentos (eixo x) e o percentual acumulado de rendimentos (eixo y). Quando os percentuais acumulados de população correspondem aos percentuais acumulados de rendimentos (10% da população com 10% dos rendimentos, por exemplo), tem se a linha de perfeita igualdade. A Curva de Lorenz representa a distribuição real de rendimentos de uma dada população tendo, em geral, formato convexo. Quanto mais afastada da linha de perfeita igualdade, mais desigual a distribuição. O índice de Gini é uma medida numérica que representa o afastamento de uma dada distribuição de renda (Curva de Lorenz) da linha de perfeita igualdade, variando de “0” (situação onde não há desigualdade) e “1” (desigualdade máxima, ou seja, toda a renda apropriada por um único indivíduo).<br> Fonte: [Síntese de indicadores sociais. Uma análise das condições de vida. IBGE, 2018.](https://biblioteca.ibge.gov.br/visualizacao/livros/liv101629.pdf)


Novamente, observa-se 6 UFs das mais desiguais figurando entre as 10 UFs mais impactadas pela pandemia. Sendo **a probilidade disso ocorrer ao acaso de menos de 7%**, há de se entender o que leva uma UF com renda altamente desigual a apresentar tal desempenho ruim no combate à covid-19.

![gini](/img/gini.png)


## Densidade demográfica

A densidade demográfica é um índice que calcula o número de habitantes por quilômetro quadrado.

Foram identificadas 5 UFs que estão entre as 10 mais densamente povoadas e que apresentam os maiores números de óbitos por covid-19 a cada 100 mil habitantes. **As chances disso ocorrer ao acaso são maiores, de pouco mais de 25%**. Pode-se desdobrar o estudo por regiões e/ou cidades dentro de cada UF, considerando que a densidade demográfica de uma mesma UF pode variar enormemente.
Ainda, pode-se estudar a possível existência de um valor-limite para a densidade demográfica abaixo do qual a taxa de transmissão é significativamente menor. Este seria um forte indicador aliado no planejamento de combate de futuras epidemias ou pandemias.

![densidade_demografica](/img/dens_demografica.png)

O aprofundamento da análise de cada um dos fatores está disponível no arquivo notebook.
Também foram sugeridos trabalhos futuros para buscar aprofundar o conhecimento das relações destes indicadores com a taxa de mortalidade por covid-19.

