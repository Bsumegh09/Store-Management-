# Electronic Store Management System

This is an Electronic Store Management System built using Spring Boot and MySQL. It allows users to manage products by adding, updating, and deleting them.
## I have also provided the products database table for reference, so you don't need to create the table separately, Spring will create table.

## Features

- **Add Product**: Allows users to add a new product to the store.
- **Update Product**: Enables users to update the details of an existing product.
- **Delete Product**: Permits users to delete a product from the store.

## Technologies Used

- **Spring Boot**: For building the backend application.
- **MySQL**: For the database management.
- **Thymeleaf**: For rendering views (optional, if you are using it).

## Requirements

- Java 17
- Spring Boot
- MySQL

## Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/electronic-store-management-system.git
    ```
    
2. **Navigate to the project directory**:
    ```bash
    cd electronic-store-management-system
    ```
    
3. **Set up the database**:
    - Create a new database in MySQL:
        ```sql
        CREATE DATABASE electronic_store_db;
        ```
    - Update the `application.properties` file with your MySQL database details:
        ```properties
        spring.datasource.url=jdbc:mysql://localhost:3306/electronic_store_db
        spring.datasource.username=your_username
        spring.datasource.password=your_password
        spring.jpa.hibernate.ddl-auto=update
        ```

4. **Build and run the application**:
    ```bash
    ./mvnw spring-boot:run
    ```

## Usage

- **Add Product**: Navigate to `/products/add` to add a new product.
- **Update Product**: Navigate to `/products/update/{id}` to update an existing product.
- **Delete Product**: Navigate to `/products/delete/{id}` to delete a product.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.


