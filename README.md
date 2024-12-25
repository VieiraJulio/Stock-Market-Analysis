### Análise de Ações | Python 

### Objetivo

O IBOV é o índice da Bovespa, que é a bolsa de valores brasileira. 
O IBOV é composto pelas ações mais negociadas na bolsa de valores brasileira. 
Para compor o IBOV, é feito um cálculo de ponderação das ações, onde as ações mais negociadas possuem maior peso no índice. O IBOV é um índice que é utilizado para medir o desempenho médio das cotações das ações mais negociadas na bolsa de valores brasileira.
Para este projeto, utilizaremos a base de dados do top 10 IBOV de maio a agosto de 2023. A base de dados foi obtida no site do Yahoo Finance.

O objetivo deste projeto é realizar uma análise detalhada das ações ao longo do tempo, com foco em compreender a variação, correção e valor das ações. 
A iniciativa busca identificar padrões e tendências de comportamento.

Este material é didático e não tem como objetivo a recomendação de compra ou venda de ativos.

Sobre as ações seguem os nomes referentes a cada uma delas e seus respectivos setores:

Código | Nome | Setor
--- | --- | ---
 VALE3 | Vale | Mineração
 ELET3 | Eletrobras | Energia Elétrica
 BBAS3 | Banco do Brasil | Bancário  
 B3SA3 | B3 | Financeiro
 ABEV3 | Ambev | Bebidas
 ITUB4 | Itaú Unibanco | Bancário
 BBDC4 | Bradesco | Bancário
 WEGE3 | Weg | Máquinas e Equipamentos
 PETR3 | Petrobras | Petróleo, Gás e Biocombustíveis
 RENT3 | Localiza | Locação de Veículos

### Detalhes das métricas utilizadas

O acompanhamento das ações ao longo do tempo é fundamental para qualquer investidor que busca tomar decisões informadas. 
Essa métrica desempenha um papel indispensável na análise e gestão eficiente de investimentos.

![image](https://github.com/user-attachments/assets/e9f695d2-b648-4a7f-b90a-37e9c64f1f75)

Ademais, as correções são ferramentas valiosas para analisar ações dentro de um mesmo segmento, permitindo identificar tendências e oportunidades com maior precisão.

![image](https://github.com/user-attachments/assets/c58628bd-c05a-4c9b-9988-e2a18d883119)

Acima foi criado todas as possibilidades de correções, dada a tendência do valor. Abaixo, essas análises foram afuniladas para as ações de bancos. 

![image](https://github.com/user-attachments/assets/bfda4ddc-0cf2-4fb5-9cd0-f428fd0e3d2e)

À vista desses resultados (não é uma recomendação de compra), as ações do mesmo setor tem uma forte correlação, ou seja, quando uma cresce outra cresce, quando uma cai outra cai. 
É possível criar mais análises para entender esse comportamento e trazer mais riqueza para o projeto. 

### Ferramentas e Metodologia

 - Matplotlib
 - Pandas
 - Itertools
 - Cycler

### Como Reproduzir o Projeto

- Baixar o arquivo ipynb e a base de dados disponíveis no repositório.
