# Online_Pizza_Delivery_System
Online Pizza Delivery System is a PHP &amp; MySQL-based full-stack web application that enables online pizza ordering with user, admin, and delivery panels, along with secure payment integration.

Online Pizza Delivery System - How to Work
=========================================

DATABASE INFORMATION:
- Database name: OPD
- Connection: localhost

USER INTERFACE:
- Home Page: http://localhost/OnlinePizzaDelivery/
- Main Index: http://localhost/OnlinePizzaDelivery/index.php
- Menu Page: http://localhost/OnlinePizzaDelivery/viewPizzaList.php
- Cart: http://localhost/OnlinePizzaDelivery/viewCart.php
- Order History: http://localhost/OnlinePizzaDelivery/viewOrder.php
- Contact: http://localhost/OnlinePizzaDelivery/contact.php

ADMIN INTERFACE:
- Admin Login: http://localhost/OnlinePizzaDelivery/admin/login.php
- Username: admin123@gmail.com
- Password: admin@123
- Admin Dashboard: http://localhost/OnlinePizzaDelivery/admin/

DELIVERY BOY INTERFACE:
- Delivery Boy Login: http://localhost/OnlinePizzaDelivery/deliveryboy/login.php
- Default credentials will be provided by admin
- Delivery Dashboard: http://localhost/OnlinePizzaDelivery/deliveryboy/

KEY FEATURES:
- User Registration & Login
- Menu browsing by categories
- Shopping cart functionality
- Multiple payment options (COD & Online via Razorpay)
- Order tracking with status updates
- Review & feedback system
- Admin order management
- Delivery boy assignment
- User profile management

SYSTEM REQUIREMENTS:
- XAMPP (Apache, MySQL, PHP)
- Modern web browser
- Internet connection (for payment gateway)

SETUP INSTRUCTIONS:
1. Install XAMPP and start Apache & MySQL
2. Place project folder in htdocs directory
3. Import OPD.sql from database folder to phpMyAdmin
4. Start Apache server
5. Access homepage via http://localhost/OnlinePizzaDelivery/

DEFAULT USERS:
- Admin: admin123@gmail.com / admin@123
- Sample delivery boy credentials are created in the database

PAYMENT GATEWAY:
- Uses Razorpay for online payments
- Test API key is configured in payment files

TROUBLESHOOTING:
- Ensure MySQL database OPD is imported
- Check database connection in _dbconnect.php files
- Verify Apache server is running
- Make sure all files are in correct directories
