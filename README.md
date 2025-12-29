A UK-based logistics company is planning to expand its global transport strategy and is seeking deeper insight into all aspects of international trade, including emerging sectors, industries, and trading partners. The company believes that access to these insights will enable it to identify growth opportunities ahead of the market and optimise their global strategy  accordingly.

UK foreign trade data was gathered from Office for National Statistics website: https://www.ons.gov.uk/datasets/trade/editions/time-series/versions

Data was cleaned and modelled using SQL. 

Data model was designed in a star schema to optimize power BI performance. Model included 3 business entities as dimension tables (date, country and industry) and a fact table containing monthly trade information.

Exploratory data analysis was conducted again using sql and then report built in power BI.

ETL was built to update report and database with new monthly information as it is published to website to allow client to see most up to date figures.


Power BI report displayed below

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/d9c7a4e7-5343-46f2-9821-cd2078100876" />
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/5fdbdb48-eaca-41dd-8323-fad8f43544d6" />



