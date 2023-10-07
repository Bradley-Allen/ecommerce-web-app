# ShipMate (E-Commerce Web App)
Made using:
- ASP.NET Core MVC, C#
- HTML, CSS, JavaScript
- Entity Framework
- Identity
- SQL Server
- Stripe (For payment handling)


## Description
Allows users to register, login, and navigate the website with authentication and authorization security measures based on roles. Users are split into 4 roles: Admin, Employee, Company, and Customer. Admins and Employees have access to view/modify all orders placed along with available products and user accounts, while company and customer accounts can only view their orders and status. Company accounts, when placing an order, are allowed a deferred payment method of 30 days while customer accounts must make the payment when the order is placed.
