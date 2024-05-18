# New Trends LLC Case Study in Power BI

## Installation
To run the project, you'll need to have the Power BI desktop installed on your pc/laptop. <br>
Download Power BI desktop from official [Microsoft Website](https://www.microsoft.com/en-us/download/details.aspx?id=58494).

## About the dataset
There are a total of five tables containing data regarding the operations of a dummy LLC called New Trends. Below are the descriptions of the columns in each table:
**Customers.csv**
| Column Name      | Description                                              |
|------------------|----------------------------------------------------------|
| Customer Key     | A unique identifier for each customer.                   |
| Contact Person   | The name of the contact person associated with the customer. |
| Company Name     | The name of the company the customer is associated with. |
| City Key         | A unique identifier for the city where the company is located. |
| City             | The name of the city where the company is located.       |
| Country          | The name of the country where the company is located.    |

**Territory.csv**
| Column Name | Description                                    |
|-------------|------------------------------------------------|
| City Key    | A unique identifier for each city.             |
| City        | The name of the city.                          |
| Country     | The name of the country where the city is located. |

**Products.csv**
| Column Name       | Description                                        |
|-------------------|----------------------------------------------------|
| Product Key       | A unique identifier for each product.              |
| Product Name      | The name of the product.                           |
| Product Group Key | A unique identifier for the product group.         |
| Product Group     | The name of the product group to which the product belongs. |
| Price (Euros)     | The price of the product in euros.                 |

**Product Group.csv**
| Column Name       | Description                                        |
|-------------------|----------------------------------------------------|
| Product Group Key | A unique identifier for the product group.         |
| Product Group     | The name of the product group to which the product belongs. |

**Sales.csv**
| Column Name       | Description                                                  |
|-------------------|--------------------------------------------------------------|
| Product Key       | Unique identifier for each product.                          |
| Product Group Key| Identifier for the group to which the product belongs.         |
| Order Date        | Date when the order was placed.                              |
| Customer Key      | Unique identifier for each customer.                          |
| City Key          | Unique identifier for each city where the order was made.     |
| Order Quantity    | Quantity of the product ordered.                             |
| Price per unit    | Price per unit of the product (in Euros).                    |
| Order Amount      | Total amount of the order (in Euros).                        |

## Summary of the report
The Power BI project comprises four pages, as shown below: *Time Analysis*, *Territory Analysis*, *Customer Analysis*, and *Product Analysis*. Each page is thoughtfully designed to offer insightful perspectives into various facets of the data.<br>
**Time Analysis:** This page serves as a comprehensive dashboard presenting vital statistics concerning sales and orders over time in card visuals. It features line plots with quarter drill down option, showing trends of sales, order quantity and number of orders. It also shows percentage variance of the same with option to toggle between Year-over-Year and Quarter-over-Quarter.<br>
**Territory Analysis:** Delving into geographical insights, this page highlights key countries and cities contributing to sales and orders. It showcases a dynamic ribbon chart depicting total sales by financial year and country, complemented by a bar chart illustrating order distribution across different countries. A unique addition is the waterfall chart, unveiling the impact of ship cities on total order quantities.<br>
**Customer Analysis:** Focused on customer-centric analytics, this page identifies top customers based on sales, order quantities, and the number of orders. A scatter chart visually represents customers alongside their total order quantities, aiding in identifying high-value clientele and consumption patterns.<br>
**Product Analysis:** Unveiling the product landscape, this page unveils the highest sales, quantities, and sale prices for individual products and product groups through succinct card visuals. A pie chart offers a holistic view of total sales distribution by product group, while the decomposition tree facilitates in-depth exploration of sales dynamics across different factors. Moreover, the inclusion of a QnA visual empowers users to pose custom queries.

## Pages from the report
<img  src="https://raw.githubusercontent.com/soumyadeepghoshGG/New-Trends-LLC-Case-Study-in-Power-BI/main/Pages/Page%201%20(1).jpg"  height=600  width=1000  alt="Page 1.1"><br><br>
<img  src="https://raw.githubusercontent.com/soumyadeepghoshGG/New-Trends-LLC-Case-Study-in-Power-BI/main/Pages/Page%201%20(2).jpg"  height=600  width=1000  alt="Page 1.2"><br><br>
<img  src="https://raw.githubusercontent.com/soumyadeepghoshGG/New-Trends-LLC-Case-Study-in-Power-BI/main/Pages/Page%202.jpg"  height=600  width=1000  alt="Page 2"><br><br>
<img  src="https://raw.githubusercontent.com/soumyadeepghoshGG/New-Trends-LLC-Case-Study-in-Power-BI/main/Pages/Page%203.jpg"  height=600  width=1000  alt="Page 3"><br><br>
<img  src="https://raw.githubusercontent.com/soumyadeepghoshGG/New-Trends-LLC-Case-Study-in-Power-BI/main/Pages/Page%204.jpg"  height=600  width=1000  alt="Page 4"><br>

## License
This project is proprietary and not open for public use. All rights are reserved by the copyright holder, Soumyadeep Ghosh. Unauthorized use, copying, modification, or distribution is prohibited.

## Contact
To collaborate or use the project, please contact me (Soumyadeep Ghosh) via mail: soumyadeepghosh57@gmail.com