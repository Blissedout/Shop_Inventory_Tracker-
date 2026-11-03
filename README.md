#SHOP INVENTORY PLATFORM

## Purpose: A platform for businesses to keep track of sales and products.

## Entities:
1.	Users: business owner 
2.	Product: Goods that are being sold
3.	Sale: number of goods sold, amount
4.	SalesItem: the product sold
5.	Category

## What Entities stores:
1.	User: name, email, password
2.	Product: name, price, quantity available, restock warning.
3.	Sale: date and time, total amount
4.	SalesItem: product, price at sale, quantity sold.
5.	Category: name

## What User does:
1.	Add product
2.	Restock
3.	View product
4.	Check sales
5.	Record Sales

## Relationships:
1.	One sale -> Many SalesItem
2.	Many SalesItem can point to one Product
3.	One User records many sales
4.	Category has many products
