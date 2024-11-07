# Plant Nursery Web Application

This project is a PHP-based e-commerce web application for a plant nursery, allowing users to browse and purchase plants. The application includes user authentication, a product catalog, shopping cart functionality, and order checkout.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication**: Users can register, log in, and maintain session-based access.
- **Product Listing**: Users can browse available plants, view product details, and add them to their cart.
- **Cart Management**: Users can add plants to their cart and view the total amount before checkout.
- **Order Checkout**: Users can place orders, which are recorded in the database.
- **Contact Form**: A contact page is available for customer inquiries.

## Installation

1. **Clone the Repository**: Clone the project to your local machine.
    ```bash
    git clone https://github.com/yourusername/plant-nursery-app.git
    ```
   
2. **Setup Database**:
   - Import the `database.sql` file provided in the project (if available) into your MySQL database.
   - Ensure tables like `users`, `cart`, `orders`, and `products` are created.

3. **Update Configuration**:
   - Open `config.php` and update the database connection details:
     ```php
     $conn = mysqli_connect("your_server", "your_username", "your_password", "your_database_name") or die('connection failed');
     ```

4. **Run the Application**:
   - Start a local server (such as XAMPP or WAMP) and place the project folder in the server's root directory.
   - Open your web browser and navigate to `http://localhost/your_project_folder`.

## Usage

1. **Homepage**: Displays an introduction to the nursery and a selection of plants.
2. **Product Catalog**: Shows available plants with options to add items to the cart.
3. **Cart**: View items added to the cart with their quantities and total price.
4. **Checkout**: Fill in delivery details and place an order.
5. **Order Confirmation**: View all placed orders in the "Orders" section.
6. **Contact**: Reach out to the nursery through the contact form.

## Folder Structure

plant-nursery-app/
├── css/
│   └── style.css           # Custom CSS for styling
├── images/                 # Folder for images
├── js/
│   └── script.js           # JavaScript functionality
├── config.php              # Database connection
├── index.php               # Homepage
├── login.php               # Login page
├── register.php            # Registration page
├── cart.php                # Cart page
├── checkout.php            # Checkout page
├── orders.php              # Orders page
└── README.md               # Project documentation


## Technologies Used

- **Front-End**: HTML, CSS, JavaScript
- **Back-End**: PHP
- **Database**: MySQL
- **Session Management**: PHP sessions

## Contributing

Contributions are welcome! Please fork this repository, create a new branch, and submit a pull request.

## License

This project is licensed under the MIT License.


