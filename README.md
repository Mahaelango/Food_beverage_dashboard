 INTRODUCTION 
❖ The dataset that is given for analysis and visualize it using dashboard were “SALES AND  PRODUCT DATA”. The dataset is collected from Kaggle and it contains mostly all the attributes essential forcreating visuals and dash boards. The dataset is available in excel (xlsx) format. 
❖ We can directly download data’s from Kaggle and import them into power bi file. A  unified, scalable platform for self-service and business intelligence in enterprises is called  Power BI. 
❖ Connect to any data, visualize it, and easily integrate the visualizations into the daily-use apps you use.Then the collected data are subjected for pre-processing. In data preprocessing it  involves filtering, cleansing, de-duplicating, validating and finally authenticating data. 
❖ Formatting the data into tables or joined tables to match target schema. Performing  calculations, translations, summarizations, changing rows and columns data type, change null  values, apply DAX measures, etc. 
❖ Power BI offers desktop-based Power BI Desktop and cloud-based BI (business intelligence) services,together referred to as "Power BI Services". 
❖ It delivers interactive dashboards, data discovery, and data preparation tools for data  warehouses. On its Azure cloud platform, Microsoft introduced a new service called Power BI  Embedded in March 2016. The product's ability to load customized visuals is one of its key  differentiators.

1.2 DATA COLLECTION 
The process of gathering, measuring, and analyzing precise insights for research using accepted, established methods is known as data collection. A researcher can assess their  hypothesis using the data that they have gathered. No of the subject of study, gathering data is  typically the first and most crucial phase in the research process. Depending on the type of data  needed, different disciplines of research require differentapproaches to data gathering. 
Dataset 
The dataset is collected from Kaggle. The dataset contains 2 tables namely 
➢ “Product.xlsx” 
NUMBER OF COLUMNS = 4 
NUMBER OF ROWS = 799 
➢ “SalesData.xlsx” 
NUMBER OF COLUMNS = 10NUMBER OF ROWS = 999+ 
The Food and Beverages Sales Analysis Dashboard provides an in-depth view of revenue  patterns, product demand, and regional performance metrics. This dashboard includes data  from various time frames and offers valuable insights for inventory management and  customer satisfaction enhancement. 
❖ https://www.kaggle.com/datasets/emmanuelbassey94/sales-and-product-data/
DATA PREPARATION AND MODELING 
DATA CLEANING 
Data cleaning is the process of removing errors from the data by filling in missing values,  smearing noisy data, analyzing and removing outliers, and smoothing noisy data. Data at  various degrees of detail mayoccasionally diverge from what is needed Missing Values – 
Appropriate values are substituted for missing values. The strategies listed below ✓ When a tuple contains many attributes with empty values, it is 
✓ Disregarded. 
✓ For the missing value, the values are manually filled in. 
✓ The values may be filled with the same global constant. 
✓ The attribute mean can replace the values that are absent. 
✓ The most likely value can be used to fill in the blanks. 
DATA TRANSFORMATION 
1. The process of changing data from one format or structure to another is known as data transformation. It is a crucial component of the majority of data management and integration  jobs, including 
2. application integration, data wrangling, data warehousing, and data integration.  Depending on the required modifications to the data between the source (initial data) and the  destination (final data), data transformation can be straightforward or difficult. The process of  data transformation often involves both manual and automated procedures. 
3. Depending on the format, structure, complexity, and amount of the data being changed, a  broad range of tools and technologies may be employed. For decades, corporations have benefited greatlyfrom using conventional data transformation techniques. 
4. Since the development of the various tools and technologies (data profiling, data visualization, datapurification, data integration, etc.), most (if not all) businesses now transform  massive volumes of data that feed internal and external applications, data warehouses, and other data repositories. 
5. So, Data Transformation is a required process in order to preprocess the loaded data set as  per our requirement and apply those changes for future use. It is while Data Analysis and  creating DAX functions of those relations respectively.
 DATA MODELLING 
Data modelling is one of the aspects used in BI tools to establish relationships between various  data sources. When using several data sources, you can construct engaging data visualizations  by defining the relationships between them. 
It can create unique calculations on the already-existing tables using the modelling capability,  and these columns can then be easily displayed in Power BI visualizations. This enables  companies to create new measures and perform unique calculations for them. 
Data Modeling is used to create relationship among the different tables in order to access the  data of different tables to visualize them. There are four types of relations that we can create as 
❖ One to One relationship 
❖ One to Many relationship 
❖ Many to One relationship 
❖ Many to Many relationship 
PROCEDURE :
DAX (Data Analysis Expressions) 
DAX is a special function that contains collection of operators, formulae, functions, expressions  to calculate, process and execute the values from existing table and return one or more values  as the result of respective functions. So, it is used to create new information from the data’s that already exist in the table whilecreating model and analyzing it. 
DAX measured of Power Bi are special functions or Programming Language that are used to  create the following such as 
➢ Calculated columns 
➢ New measures 
➢ Customized tables 
➢ Quick measures 
➢ Implement Time Intelligence 
There exist many formulae for creating the new columns, measures. The time intelligence are specialfunctions they are applicable only for the Time-based columns only. So, from these formulae and expression we can find results like maximum, minimum, average, count,sum, filters, difference, total, variance, percentage, addition, subtraction,  division, etc.… 
These are the following DAX Query:
1.Revenue = SUM (Sheet1[Sale Amount])
2.Order = DISTINCTCOUNT(Sheet1[OrderNumber])
3.ATP = DIVIDE('Product'[Revenue],'Product'[Order],"")
4.Sale Amount = Sheet1[Quantity]*Sheet1[UnitPrice]
DATA ANALYSIS AND INTERPRETATION
DATA ANALYSIS 
To turn raw data into insightful information, data analysis is the process of analyzing,  manipulating, and monitoring. Making the necessary decisions for a business or company's  growth is made easier with the use of data insights. Deep data analysis is crucial if need want to manage a firm that is data-driven. Thenit is needed to find learning different Power BI data analysis approaches fascinating and useful. 
Data analysis includes the following results 
➢Used to create various charts from Power Bi visuals 
➢Select data from various tables, analyse it and convert it into visuals. 
➢From the analysed result infer the result or final solution.
CHART QUERY :
1. Calculate the total revenue of all products? 
2. Determine the average total price of the products.  
3. Count the total number of orders across all products? 
4. Analyze revenue distribution across different sales channels? 
5. Break down revenue by each product category. 
6. Use a donut chart to visualize the distribution of orders across product  categories. 
7. Examine revenue and order trends by quarter.    
8. Show product group revenue using a bar chart for comparison. 
Highest Total Revenue of Product Group are:  
9. Track monthly revenue and order volume. 
10. Highlight the top 3 salespeople by revenue in a bar chart. 
11. Rank the top 4 salespeople based on order value. 
12. Generate a heat map to analyze orders, average transaction price  (ATP), and revenue for each salesperson. 
13. Identify the top products by revenue within each category and sales  channel? 
14. Calculate the total quantity sold, grouped by each manager? 
15. Determine the total number of orders placed through each sales  channel.
PUBLISHING DASHBOARD 
❖ Often referred to as a canvas, a Power BI dashboard is a single page that employs visuals  to convey a story. A well-designed dashboard only includes the key components of the tale  because it is only onepage long. The dashboard's tiles—the visuals you see there—are placed there by report creators. 
❖ The report page where the visualisation was made is often the page you land on after  picking a tile. A dashboard's visuals are derived from reports, and each report is built using a  single dataset. A dashboard may really be thought of as a portal to the underlying reports and  statistics. 
❖ Then it may get the report that was used to produce a visualisation by selecting  Dashboards are an excellent method to keep an eye on your company, search for solutions, and  quickly view all of your most crucial indicators. 
❖ A dashboard's visualisations might be drawn from a single underlying dataset or several,  as well as a single underlying report or many. 
❖ Regardless of where the data is stored, a dashboard may mix on-premises and cloud data  to provide a consolidated picture. A dashboard is interactive, and the tiles refresh as the  underlying data changes. It is more than simply a lovely picture.
Process of creating Dash board
STEP 1 
1. Open Power Bi serviced in web browser. 
2. From that interface click on get data at the left bottom. 
3. Select import data from device or local disk. 
4. Then import the created Power BI file of Food and Beverages Sales Analysis Dashboard.

STEP 2 
1. Now select visuals from Power Bi file created and imported to dashboard.
2. Create new dashboard named “FOOD AND BEVERAGE SALES DASHBOARD”. 
3. Then pin them to the dashboard.

Link for dashboard 
https://app.powerbi.com/groups/me/dashboards/111ee77a-9924-4fbe-98fb 5c2382a5bee2?experience=power-bi 
