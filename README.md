# Food_Price_Dashboard
Excel Dashboard showing food price trends by country(2018-2022)
Countries Food Price Dashboard
Dashboard Overview
This dashboard visualizes food price trends across multiple countries from 2018 to 2022.
It provides insights into average prices, trends over time and country specific comparisons in USD.

Dataset
•	Columns: Country, Year, Month, Food Item, Unit of Measurement, Average Price, Currency, Price in USD, Availability, Quality
•	Years: 2018–2022
•	Source: Kaggle.com
•	Purpose: To compare food prices between countries, observe trends and visualize price behavior in USD.

Tools & Techniques
•	Excel (Pivot Tables, Pivot Charts, Slicers)
•	Data Cleaning & Formatting
•	KPI Cards
•	User-friendly interactivity

Data Cleaning Steps
•	Formatted Year, Month, and Availability columns as Number
•	Fixed decimal inconsistencies (for example price shown as 1,00 to 1.00)
•	Used =H2 / VLOOKUP(D2, $L$2:$N$5, 3, FALSE) formula to standardize the prices

•	Replaced #VALUE! Errors and ensured all numeric fields contained real numbers

Dashboard Features
•	KPI Cards:
o	Total Items
o	Average Price USD
o	Max Price
•	Visuals: 
o	Pie Chart: Average Price by Food Item
o	Bar Chart:  Average Price per Country
o	Line Chart: Price Trend Over Time
o	Clustered Column Chart: Food Item Price per Country
•	Interactive Year Filter (Slicer)
Key Insights
•	Food prices increased steadily from 2018 to 2022
•	South Africa had the lowest average food item prices
•	Sweden and Japan had the highest
•	Bread and Milk had the most stable price trends
