# HW5
Задание №5 курса Data Science

Реализовать минимум 5 регрессоров, сравнить метрики между собой, выбрать лучший для датасета. Можно использовать любой датасет

В работе был использован датасет USA Macroeconomic Rate Of Changes 1993-2025
Датасет содержит следующую информацию о макроэкономических показателях США за период 1993-2024 гг. в разрезе месяцов:

Industrial Production: Monthly data on the total output of US factories, mines, and utilities.
Manufacturers' New Orders: Durable Goods: Measures the value of new orders placed with manufacturers for durable goods, indicating future production activity.
Consumer Price Index (CPIAUCSL): A measure of the average change over time in the prices paid by urban consumers for a market basket of consumer goods and services.
Unemployment Rate: The percentage of the total labor force that is unemployed but actively seeking employment.
Retail Sales: The total receipts of retail stores, indicating consumer spending and economic activity.
Producer Price Index: Measures the average change over time in the selling prices received by domestic producers for their output.
Personal Consumption Expenditures (PCE): A measure of the prices paid by consumers for goods and services, used in calculating inflation.
National Home Price Index: A measure of changes in residential real estate prices across the country.
All Employees, Total Nonfarm: The number of nonfarm payroll employees, an important indicator of the labor market.
Labor Force Participation Rate: The percentage of the working-age population that is either employed or actively looking for work.
Federal Funds Effective Rate: The interest rate at which depository institutions lend reserve balances to other depository institutions overnight.
Building Permits: The number of building permits issued for residential and non-residential buildings, a leading indicator of construction activity.
Money Supply (M2): The total money supply, including cash, checking deposits, and easily convertible near money.
Personal Income: The total income received by individuals from all sources, including wages, investments, and government transfers.
Trade Balance: The difference between a country's imports and exports, indicating the net trade flow.
Consumer Sentiment: The index reflecting consumer sentiment and expectations for the future economic outlook.
Consumer Confidence: A measure of how optimistic or pessimistic consumers are regarding their expected financial situation and the economy.

По метрике R^2 для предсказания Индекса потребительских цен наиболее эффективным оказался регрессор, использующий метод К-ближайших соседей
