# GastosPresidentes

Foi feita a análise de dados dos gastos presidenciais no cartão corporativo desde 01/2013 (primeira data disponível no site governamental) até 03/2022.</br>
A fonte dos dados são uma série de arquivos .csv baixados da página https://www.portaltransparencia.gov.br/cartoes/consulta com filtros de período e orgão ao qual o cartão está vinculado, nesse caso, "20101 - Presidência da República". </br>
As informações de inflação mensal foram tiradas do site https://www.idinheiro.com.br/tabelas/tabela-ipca/</br></br>
Os dados foram extraídos com auxílio da biblioteca pandas a qual tem funções de extração tanto de arquivos .csv quanto de páginas em formato html.</br>
Depois foram tratados, atualizados e somados de acordo com o mandatário até o mês de Abril de 2022 para que a comparação fosse mais justa do ponto de vista do valor atual em real.</br>
E por fim foi feito um gráfico em barras com a biblioteca matplotlib para uma visualização mais fácil.</br></br>

# PresidentExpenditures

The data analysis of the presidential expenditure on corporate cards since 2013/01 (first available date to extract data) until 2022/03.</br>
The data source is a series of files downloaded from the webpage https://www.portaltransparencia.gov.br/cartoes/consulta filtered by period and government branch, in this case "20101 - Presidência da República".</br>
The monthly inflation data were gathered from https://www.idinheiro.com.br/tabelas/tabela-ipca/ </br></br>
All the data were extracted with the help of pandas library which can be used for .csv files and html pages.</br>
After data wrangling, update and aggregation they were separated by presidential mandate until April of 2022 to make the comparison fairer on the viewpoint of actual value of money.</br>
And to finish it was plotted a bar chart with the help of matplotlib library to promote an easier visualization.
