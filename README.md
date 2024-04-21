<h1>The Look Ecommerce Sales dashboard</h1>
<h2>Dataset Used</h2>
<p><a href="https://console.cloud.google.com/bigquery?ws=!1m4!1m3!3m2!1sbigquery-public-data!2sthelook_ecommerce">Bigquery Public Dataset- thelook_ecommerce</a>  </p>
<h2>What is it ?</h2>
<p>This interactive dashboard provides insights on sales revenue related datapoints for the ecommerce platform "The Look".A Fictitious E-Commerce Dataset fro Google Bigquery public dataset is the source for this dashboard.This dashboard has Sales revenue,Profit,Margin and total orders for the sales.This also provide insights of revenue and profit across different distribution centers and total revenue and profit over the period. </p>
<h2>DAX Used</h2>
<p>ORDER_YEAR - Year extracted from column "created_at" in format MM/DD/YYYY HH:MM:SS <br>
ORDER_MONTH - Month extracted from column "created_at" in format MM/DD/YYYY HH:MM:SS<br>
ORDER_DATE - Date extracted from column "created_at" in format MM/DD/YYYY HH:MM:SS<br>
COST - Cost Price lookedup from table "products" with "product_id" as reference<br>
Profit - calculated by formule (sale_price-COST)<br>
Profit Margin - calculated by formula (Profit/sale_Price)<br>
distribution_center_name - looked up from table "inventory_items" with "inventory_item_id" as reference<br>
 
</p>
