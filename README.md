In this project I visualized data that was "collected" from a manufacturing facility. 

Three dynamic dashboards were created.
1. A customer data dashboard
2. A manufacturing/production dashboard
3. An Order data dashboard

PowerQuery was used to bring int he raw data from an excel workbook, however in practice this would be a sql server.
The raw data was merged and appended into a star schema with the order data being the center of the star. With other tables relating to product, customer, and production data.

Each dashboard has bookmark buttons to navigate between the different reports. The graphs use field parameters for multiple x and y axis selections. 
The bar chart uses conditional formatting. With the allowable range showed in green. 
Dax was used to create multiple measures shown within the report. 

