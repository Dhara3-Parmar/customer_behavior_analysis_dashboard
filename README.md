...Project Overview...
This comprehensive data analytics project aims to decode the shopping patterns of 3,900 customers to help a retail business optimize its marketing strategies. By integrating a PostgreSQL database with Power BI, I transformed raw transactional data into a dynamic, interactive storytelling dashboard.

🛠️ Technical Workflow
Data Extraction: Connected Power BI Desktop to a local PostgreSQL server using Npgsql providers.
Data Transformation (Power Query):
Handled missing values and standardized data formats.
Created a custom "Age Group" column using conditional logic to segment customers into Young Adults (<=30), Middle-aged (31-50), and Seniors (51+).
Data Modeling: Established relationships within the public.shopping_data table to ensure accurate cross-filtering.

📈 Key Insights & Visualizations
Executive Summary: Displayed high-level KPIs including a Total Revenue analysis and an Average Purchase Amount of $59.76.
Customer Demographics: A Donut Chart representing the subscription split, showing that ~27% of customers are premium subscribers.
Revenue by Category: A Bar Chart identifying Clothing and Accessories as the primary revenue drivers.
Age-Based Trends: Leveraged the custom Age Group column to identify that Young Adults contribute the highest revenue share (~$62K).

💻 Skills Demonstrated
SQL Database Management (PostgreSQL)
Data Visualization & Storytelling (Power BI)
ETL Processes (Power Query & DAX)
