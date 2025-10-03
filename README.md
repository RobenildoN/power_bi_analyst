# power_bi_analyst

Repositório relacionado a formação de Power BI Analyst

Desafio 3
Ponto 13 desafio 3 - não se pode atribuir pois há mais de uma localização com o mesmo departamento
![Desafio 3](https://github.com/RobenildoN/power_bi_analyst/blob/main/Desafio%203.png)

Desafio 4

![Desafio 4](https://github.com/RobenildoN/power_bi_analyst/blob/main/Desafio%204.png)

Desafio Modelagem de dados
as funções usadas no DAX foram:
D_Calendario = 
var dataminima = DATE(YEAR(MIN(financials_origem[Date])),1,1)
var datamaxima = DATE(YEAR(MAX(financials_origem[Date])),12,31)
RETURN
CALENDAR(dataminima,datamaxima)

Year = D_Calendario[Date].[Ano]

Month = D_Calendario[Date].[MonthNo]

![Desafio Modelagem](https://github.com/RobenildoN/power_bi_analyst/blob/main/Desafio%20Modelagem.png)

