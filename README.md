# uzima_chicken-_ussd
Uzima Chicken Ordering System is a USSD (Unstructured Supplementary Service Data) application that enables users to conveniently order chicken from Uzima Chicken. It offers features like registration, order placement, order updates, and order history review.

How It Works
User Registration:
Users dial the USSD code provided by the Telco network.
They follow the prompts to register by providing their name, national ID, phone number, address, and PIN.
Alternatively, users can register by sending an incoming message with the required details.
Order Placement:
Registered users select the option to place an order from the main menu.
They choose the type of chicken (e.g., meat or laying chicken) and specify the quantity.
After confirming the order, it is processed, and the total cost is displayed.
Order Update:
Users can update the quantity of their pending orders if needed.
They select the order to update and enter the new quantity along with their PIN for confirmation.
Order History:
Users can review their order history to track previous orders.
They enter their PIN to view their order history, which includes details like order ID, chicken type, quantity, total cost, and delivery status.
Technology Stack
Language: PHP
Database: MySQL
Web Server: Apache (XAMPP)
USSD Gateway: Integrated with Telco network's USSD gateway
Running the Application
Database Setup:
Create a MySQL database named uzima.
Import the SQL file uzima.sql to create necessary tables.
Server Configuration:
Deploy the PHP application on a web server (e.g., Apache).
Ensure PHP and MySQL are installed and configured.
USSD Integration:
Integrate the application with the USSD gateway provided by the Telco network.
Implement incoming message handling for registration via messages.
Accessing the Application:
Users can dial the USSD code provided by the Telco network to access the application.
Alternatively, they can register by sending an incoming message with the required details.

and it use incomming message for shortcode to make registration
