# Build an Ecommerce data warehouse using SSIS combined with Power BI for analysis
### Introduction:
   DataCo Global's supply chain dataset. Includes the company's transactions with customers. The dataset includes 53 attributes ranging from order and shipping information to sales information, 180,519 rows, and features that include a mix of text and numeric data, such as location orders and sales data. Specifically, there are 24 character columns and 28 numeric columns.
  
  Data resource: https://data.mendeley.com/datasets/8gx2fvg2k6/5/files/72784be5-36d3-44fe-b75d-0edbf1999f65
  
   + 24 character columns and 28 numeric columns.
   + 180,519 (rows) * 40 (columns)
![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/029eacf7-5ca4-4213-87fd-762bc9b506a4)

    Based on the data set, we need to provide reports on overall sales as well as details of each product based on each different attribute in the data set and make comments on how the product operates. transportation methods thereby improve efficiency. In addition, it is possible to compare the sales performance of different countries and regions.
### Required
+ Visual studio code 2019
+ SQL Server Integration Services
+ SQL server - express 2019
+ PowerBI
+ ...
### From those requirements, the data warehouse will have:
- Using SSIS to built datawarehouse

• Two Fact tables include FactSales and FactDelivery, both of which are of type Transactions. Business process of each Fact version:

 FactSales: Used to analyze and report sales, profits and sales quantity of each product according to each attribute.

 FactDelivery: Report on the activity of shipping orders to users

• Dim tables include: DimDepartment, DimShippingMode, DimTime, DimMarket, DimRegion, DimSegment, DimCustomer, DimCountry, DimCity, DimCategory

Fact Sales: 
![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/a9b4cf17-3145-4ae8-8344-98b4a533057c)
Fact Delivery:
![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/2bb6b5eb-b247-4869-8ac1-82aee77d83c7)
Constellation Schema:
![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/6d15c7b8-16c4-4f01-8d78-ece21034b103)

Integrate data into the warehouse (SISS)
![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/ae97b4e8-29e2-40ea-8e1c-b69324ae4adb)

![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/a6ee31f3-d627-4405-a5ab-81780897ec85)


### Data analysis
After successfully ETL and building a data warehouse, we will use Power BI to visualize, analyze data, etc.
+ Revenue Dashboard

![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/462cffd2-94b1-4d1d-baa6-6fb4d9bb4a49)
+ Shipping status Dashboard

 ![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/a944a2a5-ab41-437b-9a45-b7eee9a68186)

 + Manage product Dashboard

![image](https://github.com/lonGDiBo/DataWareHouse_Retail/assets/115699195/c9454ce5-a052-4c62-8661-e6c322c9cb40)
Dashboard shows us the total quantity of products: you can choose to view the quantity by market, region, country and even by certain time. There is also a map chart to track the number of products sold in the region and compare between regions or between markets or countries.

## Nice try
