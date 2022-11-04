Portugês
criado, escrito e traduzido por: [Hylan Silva](https://github.com/hylansilva)<br>
Recife, 04 de Novembro de 2022

# Dataset de Varejo

## Sobre o Dataset

### Conteudo

VocÇe receberá dados históricos de vendas, de uma rede com 45 lojas localizadas em diferentes regiões, cada lloja contém um determinado número de departamentos. A empresa faz eventos de promoçionais ao longo do ano. Esses eventos precedem feriados que virão a ocorrer, os Quatros maiores são:
* Super Bowl
* Dia do Trabalho
* Ação de Graças
* Natal

As semanas com esses feriados tem peso 5 vezes maior na avaliação, do que as semanas sem feriados.

Dentro da planilha excel, tem 3 abas - 
1. [Stores(Lojas)](../dataAnalyst/data/stores-data-set.csv)
2. [Features(Caracteristicas)](data/features-data-set.csv)
3. [Sales(Vendas)](../dataAnalyst/data/sales-data-set.csv)



<hr>
English 
created, written and translated by: [Hylan Silva](https://github.com/hylansilva)<br>
Recife, November 4, 2022

# Retail Dataset

## About Dataset
### Context
The Challenge - One challenge of modeling retail data is the need to make decisions based on limited history. Holidays and select major events come once a year, and so does the chance to see how strategic decisions impacted the bottom line. In addition, markdowns are known to affect sales – the challenge is to predict which departments will be affected and to what extent.

### Content
You are provided with historical sales data for 45 stores located in different regions - each store contains a number of departments. The company also runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks.

Within the Excel Sheet, there are 3 Tabs – Stores, Features and Sales

### Stores
Anonymized information about the 45 stores, indicating the type and size of store

### Features
Contains additional data related to the store, department, and regional activity for the given dates.

* Store - the store number
* Date - the week
* Temperature - average temperature in the region
* Fuel_Price - cost of fuel in the region
* MarkDown1-5 - anonymized data related to promotional markdowns. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA
* CPI - the consumer price index
Unemployment - the unemployment rate
* IsHoliday - whether the week is a special holiday week
### Sales
Historical sales data, which covers to 2010-02-05 to 2012-11-01. Within this tab you will find the following fields:

* Store - the store number
* Dept - the department number
* Date - the week
* Weekly_Sales -  sales for the given department in the given store
* IsHoliday - whether the week is a special holiday week
#### The Task
1. Predict the department-wide sales for each store for the following year
2. Model the effects of markdowns on holiday weeks
3. Provide recommended actions based on the insights drawn, with prioritization placed on largest business impact