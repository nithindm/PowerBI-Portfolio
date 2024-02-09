# CAR SALES 

## DASHBOARD :

![cars](https://github.com/nithindm/PowerBI-Portfolio/assets/159453441/26b220fa-69bd-4693-bcec-0240b92efa13)

![cars 2 re](https://github.com/nithindm/PowerBI-Portfolio/assets/159453441/4d19e872-824c-4349-a81b-2816cc6e5736)

## OBJECTIVE : 
The objective of this project is to design and develop a dynamic and interactive Car Sales Dashboard using Power BI. The dashboard will visualize critical KPIs related to our car sales, helping us understand our sales performance over time and make data-driven decisions.

## PROBLEM STATEMENT 1:

## KPI'S Requirement :

### 1. Sales Overview:

- Year-to-Date(YTD) Total sales 
- Month-to-Date (MTD) Total sales
- Year-over-Year (YOY) Growth in Total Sales
- Difference between YTD sales and Previous Year-to-Date (PYTD)sales

### 2. Average price Analysis :

- YTD Average Price
- MTD Average Price 
- YOY Growth in Average Price 
- Difference between YTD Average price and PYTD Average Price 

### 3. Cars Sold Metrics :

- YTD Cars Sold 
- MTD Cars Sold 
- YOY Growth in Cars Sold 
- Difference between YTD Cars Sold and PTYD Cars Sold 

## PROBLEM STATEMENT 2: 

## Charts Requirement :

### 1. YTD Sales Weekly Trend:
- Display a line chart illustrating the weekly trend of YTD sales. The X-axis should represent weeks, and the Y-axis should show the total sales amount.

### 2. YTD Total Sales by Body Style:
- Visualize the distribution of YTD total sales across different car body styles using a Pie chart.

### 3. YTD Total Sales by Color: 
- Present the contribution of various car colors to the YTD total sales through a pie chart.

### 4. YTD Cars Sold by Dealer Region: 
- Showcase the YTD sales data based on different dealer regions using a map chart to visualize the sales distribution geographically.

### 5. Company-Wise Sales Trend in Grid Form: 
- Provide a tabular grid that displays the sales trend for each company. The grid should showcase the company name along with their YTD sales figures.

### 6. Details Grid Showing All Car Sales Information: 
- Create a detailed grid that presents all reevant information for each car sale, including car model, body style, colour, sales amount, dealer region, date, etc.

## DATA CLEANING :

- Import dataset in powerBI 
- Transform data's from PowerBI to Power Query
- Initially , check it out column quality and column distribution 
- if in dataset to be cleared any null values, errors , replace value etc , just clear that.
- check it out each column and its appropriate data types 

## DATA PROCESSING : 

- In requirement mostly have some time intelligence calculation KPI'S like YTD , MTD and etc . 
- So for that , we should make a calendar table . Because dataset didn't have proper date columns like individual month , year and etc.
- create year , month , week , month no columns through Date column.

## DATA MODELING : 

- After create calendar table , we have to joins with existing dataset.
- Because when calculating time intelligence functions that could be proper result . 

## DATA ANALYZE  

- According to client requirement , we need some time intelligencesales  report . 
- For that , calculate YOY , MTD , YTD , PYTD ,Sales Difference and etc stuffs through DAX Functions        

## DATA VISUALIZATION : 

According to client requirments , 

- Create Total sales , Average price and Car sold metrics for KPI'S through card visuals. 

  ![kpi 2](https://github.com/nithindm/PowerBI-Portfolio/assets/159453441/a20cfcad-e711-4ce5-80f6-512501b28253)

- Create a line chart for YTD Sales Weekly Trend

  ![line](https://github.com/nithindm/PowerBI-Portfolio/assets/159453441/7f3000b9-0755-42ff-9b90-c74f1955c061)

- Create YTD Total Sales by Body Style and YTD Total Sales by Color using pie chart

  ![don](https://github.com/nithindm/PowerBI-Portfolio/assets/159453441/842fb982-1867-4076-b60c-401e43f00bdd)


- Create a map chart for YTD Cars Sold by Dealer Region

  ![map](https://github.com/nithindm/PowerBI-Portfolio/assets/159453441/3a9bfd60-d934-4874-8c23-4766ed5a70bd)

- Create a Table visual for Company-Wise Sales Trend

  ![table](https://github.com/nithindm/PowerBI-Portfolio/assets/159453441/4e06f579-9bdc-4713-9eed-b630faa2234c)

- Finally , Make another sheet called Details then put in Details Grid Showing All Car Sales Information and KPI's 

  ![cars 2 re](https://github.com/nithindm/PowerBI-Portfolio/assets/159453441/4d19e872-824c-4349-a81b-2816cc6e5736)
  
## DASHBOARD :
- Arrange created all charts and KPI's in Dashboard
-  Add Body style , Dealer_name , Transmission , Engine as filters from Dataset 
- Add navigator for connect to overview and Details
- Format All graphs and KPI'S as well


 # PowerBI-Portfolio
