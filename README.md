# Restaurant-Menu-Ordering-System

# Project Overview
The Restaurant Menu Ordering System is a Windows-based application developed using **VB.NET** and **MSSQL Express Edition**. It facilitates food ordering and payment for both customers and staff, providing features for browsing the menu, placing orders, and managing restaurant operations. This system includes modules for handling customers, staff, promotions, menus, and orders.

**My Role**: I was responsible for developing the **Order and Payment Module**, which allows customers to add items to cart, place orders, choose payment methods, and track the status of their orders. In addition, my module also allows staff (employees and managers) to manage the restaurant orders, update order status, process order payments, and managers can also generate the order transaction report.

# Technologies Used
- **VB.NET**: Used for creating the user interface and business logic.
- **MSSQL Express Edition**: Used as the database to store system records.
- **Visual Studio 2022**: Used as the integrated development environment (IDE) for the project.

# Order and Payment Module Features
This module enables customers to browse, order, and pay for menu items, as well as staff to manage orders.

# 1. Add Items to Cart
- Customers can browse menu items through categories such as **Foods**, **Beverages**, and **Desserts**, as well as sub-categories like **Chicken** under the category **Foods**.
- The system limits each item in the cart to a maximum of 10 units.
- Sold-out items are disabled, and customers cannot add them to their cart.

# 2. View Cart
- Displays the selected items, their quantities, and total price.
- Customers can adjust quantities or remove items from the cart.
  
# 3. Proceed to Payment
- Customers can choose between two payment methods:
  - **Cash**: The customer pays at the counter.
  - **Credit Card**: The system validates the credit card information, including card number, CVV, and expiration date.

# 4. Confirm Order
- Once payment is confirmed, the order is placed, and the order will be sent to the staff side for monitoring.
- Customer can also monitor the order status.
- For credit card payments, the order is automatically sent to the kitchen without staff confirmation.

# 5. Order Status Tracking
- Staff can monitor and update the order status through the following stages:
  - **Waiting for Accept**: The order is placed by the customer.
  - **Received**: The order is accepted by the staff.
  - **Preparing**: The kitchen is preparing the order.
  - **Ready**: The order is ready for serving.
  - **Completed**: The payment is made, and the order is concluded.

# 6. Payment Completion and Receipt
- Cash payments are processed through a POS interface, and a receipt is generated for both cash and credit card payments.
- **Membership Points**: If the customer is a member, they earn points when an order is completed.

# 7. Order Reports
- **Sales Reports**: Managers can generate sales reports for any selected time period, providing insights into transaction totals and performance.

# Database Information
The system uses an **MSSQL Express Edition** database to store all system information. The database is integrated into Visual Studio, and the .mdf file is included in the project.

# How to Run the Project
1. Download the "Assignment.zip" file from this repository, and unzip it in your computer.
2. Open the project in **Visual Studio**.
3. Change the startup form of the system by:
- right click the "Assignment" at the project level, and click "Properties"
- In the Application section, under Startup form:, choose:
  - For Customer side:
    - FrmLoginPage
  - For Staff side:
    - frmHomePage

# Credits
- **Team Members**:
  - Chin Wei Lun – Staff Module
  - Daniel Yong Xian – Customer and Membership Module
  - Khong Wei Xian – Promotion Module
  - Chong Jing Yan (me) – Order and Payment Module
  - Stanley Chong Shi Wen – Menu Module
