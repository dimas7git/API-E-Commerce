# E-commerce API

## Overview

This is a simple E-commerce API built with Flask, Flask-SQLAlchemy, Flask-Login, and Flask-CORS. The API allows you to manage products, user authentication, and shopping cart functionalities.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/ecommerce-api.git
    ```

2. Change into the project directory:

    ```bash
    cd API-E-Commerce
    ```

3. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the application:

    ```bash
    cd app 
    python main.py
    ```

   The API will be accessible at http://localhost:5000.

## API Documentation

API documentation is available in the Swagger YAML file `swagger.yaml`. You can use tools like Swagger UI to interact with and test the API.

## API Endpoints

- `/login`: User authentication endpoint.
- `/logout`: User logout endpoint.
- `/api/products`: Product management endpoints.
- `/api/cart`: Shopping cart endpoints.
