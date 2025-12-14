A UK-based logistics company is planning to expand its global transport strategy and is seeking deeper insight into all aspects of international trade, including emerging sectors, industries, and trading partners. The company believes that access to these insights will enable it to identify growth opportunities ahead of the market and optimise their global strategy  accordingly.

UK foreign trade data was gathered from Office for National Statistics website: https://www.ons.gov.uk/datasets/trade/editions/time-series/versions

Data was cleaned and modelled using SQL. 

Data model was designed in a star schema to optimize power BI performance. Model included 3 business entities as dimension tables (date, country and industry) and a fact table containing monthly trade information.

Exploratory data analysis was conducted again using sql and then report built in power BI.

ETL was built to update report and database with new monthly information as it is published to website to allow client to see most up to date figures


Power BI report displayed below

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/c3370cdd-3f34-46fc-ab12-0477bc9fb5a5" />   <img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/6a0ba0e5-b037-4f2c-8688-100cf63047b6" />


