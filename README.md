# Advanced POS System

An advanced Point of Sale System (POS) project built using PHP and MySQL. This web application is designed to streamline inventory management, sales tracking, and payment processing for businesses. It provides a comprehensive solution with features tailored for both administrators and employees.

## Features

### Admin Panel
- Manage customers, users, products, and categories
- Add and update customer records with details like name, email, ID, address, contact, and date of birth
- Manage employee users with different access levels
- View dashboard with an overview of products, sales, graphs, and more
- Set profit margin and tax percentage for products

<img src="https://github.com/Dhaval-pathak/POS-System-PHP/assets/93087161/02bbfeb1-0823-4ec3-8c90-9eed5d7cfe97" alt="description" width="700" height="400">

##

### Product Management
- Add and manage product categories
- Add new products with details like code, description, stock quantity, buying price, and image
- Automatic selling price calculation based on profit margin
- Stock level indicators (green for sufficient stock, red for low stock)
- Update product details and stock quantities

<img src="https://github.com/Dhaval-pathak/POS-System-PHP/assets/93087161/47697c3d-9f0c-4064-961a-a2d5de7c3d14" alt="description" width="500" height="300">
<img src="https://github.com/Dhaval-pathak/POS-System-PHP/assets/93087161/e94848cf-2003-4919-8ad5-5166f4d3158d" alt="description" width="500" height="300">

##



### Sales Management
- Create new sales by selecting customers and adding products
- Update product quantities in the sales order
- Multiple payment methods (cash, credit card, debit card)
- Generate invoices with unique invoice numbers and seller details
- Update existing sales records
- Export sales data in XML format or download receipts as PDF

<img src="https://github.com/Dhaval-pathak/POS-System-PHP/assets/93087161/c15013de-cb89-43f9-93e6-8ce34f97034c" alt="description" width="500" height="300">
<img src="https://github.com/Dhaval-pathak/POS-System-PHP/assets/93087161/92cfa267-8392-42c7-8dee-b56fd4c24f9c" alt="description" width="500" height="300">

##

### Reporting
- Sales reports with graphical representations (bar graphs, pie charts)
- Monthly sales transactions with total sales figures
- Best-selling products report
- Top sellers report based on products sold
- Top customers report based on purchases

<img src="https://github.com/Dhaval-pathak/POS-System-PHP/assets/93087161/8029d29c-31fe-4bf4-b02f-3d733875ba6a" alt="description" height="300">

##

### Other Features
- Search and filter records
- User management with different access levels
- Clean and user-friendly dashboard with Bootstrap UI

<img src="https://github.com/Dhaval-pathak/POS-System-PHP/assets/93087161/7a73c163-6301-47cb-8504-263dfe635d20" alt="description" height="300">


## Getting Started

### Prerequisites
- PHP version 5.6 or later
- MySQL database

### Installation
1. Clone the repository or download the project files.
2. Extract the project files to your local web server's document root (e.g., `htdocs` folder in XAMPP).
3. Create a new MySQL database with the name provided in the `LOGIN DETAILS` file.
4. Import the database file (`DATABASE FILE/posystem.sql`) into the newly created database using phpMyAdmin or a similar tool.
5. Navigate to `http://localhost/[PROJECT_FOLDER_NAME]/` in your web browser.
6. Log in using the credentials provided in the `LOGIN DETAILS` file.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments
- [Bootstrap](https://getbootstrap.com/) - CSS framework used for UI components
- [Vanilla CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - Styling for custom UI elements
