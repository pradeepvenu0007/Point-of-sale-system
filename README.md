# Point-of-sale-system

POS (Point of Sale) is a system to manage the sales in a retail store. When a customer arrives at the POS counter with the products/goods to purchase, the cashier will start a new sale transaction. When the sale transaction is complete, the customer pays in cash, card or UPI. After the payment is successful, a receipt will be printed.

Users / Actors:
1. Admin - will create staff, add a new inventory, update stocks
2. Staff/cashier - staff can sale products to the customers and invoke a purchase receipt
3. Customer/Client - buy new products 

About Admin:
1.Admin user credential (username and password) will be created implicitly.
2.The users (admin and staff) need to enter their credentials to access as admin or staff. The system shows the admin dashboard or staff dashboard depending on their roles.
Admin Dashboard:
1. From this dashboard, admin can manage stock, sales report, update user (admin and staff) credentials  / Details and customer service.
2.Stock Management:
-In the stock management page, the admin can add a new product by giving the product a unique id (can be manually entered or automatically generated).
-The product details should include Max retail price (MRP), category, brand, date added, quantity, tax, expiry date etc. 
-The admin can update the existing stock details. 
-Stock report: Admin can view overall stock. The admin can search products by product id and name. The admin can also filter products by date, name, price and quantity.
-The product with low quantity (less than 10 in stock) should be highlighted with a specific colour or notified to the admin.
-The product to be expired will be highlighted with a colour.
-The product expired will not be sold.
-Admin can delete a product from stock.
-Admin can remove the product quantity from the stock.
3. Sales Report
-Admin can view overall sales report -the products sold. 
-Can generate sales based on From and To date
-The admin can print as a pdf.
4: Staff Registration / Admin Management
-Admin can add, delete or update staff and their credentials / details.

## Technologies Used
*Java
* Angular 4
* Spring Data
* Spring Boot
* Spring Framework
* MySQL
* Github
* Maven
* Jenkins

## Features

List of features ready and TODOs for future development
About Admin:
1.Admin user credential (username and password) will be created implicitly.
2.The users (admin and staff) need to enter their credentials to access as admin or staff. The system shows the admin dashboard or staff dashboard depending on their roles.
Admin Dashboard:
1. From this dashboard, admin can manage stock, sales report, update user (admin and staff) credentials  / Details and customer service.
2.Stock Management:
-In the stock management page, the admin can add a new product by giving the product a unique id (can be manually entered or automatically generated).
-The product details should include Max retail price (MRP), category, brand, date added, quantity, tax, expiry date etc. 
-The admin can update the existing stock details. 
-Stock report: Admin can view overall stock. The admin can search products by product id and name. The admin can also filter products by date, name, price and quantity.
-The product with low quantity (less than 10 in stock) should be highlighted with a specific colour or notified to the admin.
-The product to be expired will be highlighted with a colour.
-The product expired will not be sold.
-Admin can delete a product from stock.
-Admin can remove the product quantity from the stock.
3. Sales Report
-Admin can view overall sales report -the products sold. 
-Can generate sales based on From and To date
-The admin can print as a pdf.
4: Staff Registration / Admin Management
-Admin can add, delete or update staff and their credentials / details.

About Staff:
1. The staff user credentials will be provided by the admin. //forgot password
2.Staff need to enter their credentials to access them as staff. The system shows the staff dashboard.
3. New Transaction:
-The staff needs to enter / search the products by product Id or name
-Available quantity and Price per unit will be automatically displayed
-Number of quantities should be entered
-A discount percentage will be given to regular customers.
-Total value to be paid is calculated automatically (Total price = (number of quantities * product price - discount) + Tax)
-Following, the customer details (Name, phone number, mail and address) and mode of payment should be entered before the receipt is generated.
-Once the payment is received, a receipt with unique receipt id (automatically generated), customer details (Name, phone number, mail), price to be paid and tax details should be printed.
4. Sales information:
-Staff can search the sales information based on date, customer name and mobile.
-Staff can print the receipt stored in the cloud.

To-do list:
- Home Delivery
- Loyalty points - Points will be added to a customer based on his total price. (For example: 1000 total price = 10 points)
- Admin - the system allows them to view sales insights - the admin can view products in high demand, products in low demand, total transactions this year.
## Getting Started
   
git clone https://github.com/pradeepvenu0007/Point-of-sale-system/tree/main Front-end

open cmd
navigate to project file
run npm install
run ng server command Back-end
open project in spring boot suite
run project as spring boot application

## License

This project uses the following license: [Pradeep K V]https://github.com/pradeepvenu0007).

