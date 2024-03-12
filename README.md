# E-Commerce Website - Laravel Project

This project is a basic CRUD application for an e-commerce website built using the Laravel framework.

## Stack

- PHP - Laravel Framework
- Bootstrap CSS
- MySQL Database

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. Development is made enjoyable and creative with Laravel, as it takes the pain out of common web development tasks.

## Setup

### Prerequisites

- Docker
- Docker Compose
- PHP (for local development)
- Composer (for local development)
- MySQL (for local development)

### Installation

1. Clone the repository:

2. Navigate to the project directory:

   ```bash
   cd your-laravel-project
   ```

3. Create a `.env` file based on the provided `.env.example`:

   ```bash
   cp .env.example .env
   ```

4. Modify the `.env` file to configure your environment variables, including the database settings and mail settings.

### Running with Docker Compose

1. Start the Docker containers:

   ```bash
   docker-compose up -d
   ```

2. Access the application at [http://localhost](http://localhost) in your web browser.

### Local Development

1. Install dependencies:

   ```bash
   composer install
   ```

2. Start the development server:

   ```bash
   php artisan serve
   ```

3. Access the application at [http://localhost:8000](http://localhost:8000) in your web browser.

## Usage

Once the application is running, you can perform the following tasks:

- **Register a User**: Create an account on the e-commerce website.
- **Browse Products**: View the list of available products.
- **Add Products to Cart**: Select products and add them to your shopping cart.
- **Checkout**: Proceed to checkout and complete the purchase.
- **Manage Products (Admin)**: As an admin, you can add, edit, and delete products.

## Contribution

Contributions are welcome! If you want to contribute to the development of this project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request with a detailed explanation of your changes.

## Environment Variables

You need to configure the following environment variables in your `.env` file:

- `APP_NAME`: Name of your Laravel application
- `APP_ENV`: Application environment (`local`, `production`, etc.)
- `APP_KEY`: Application key
- `APP_DEBUG`: Debug mode (`true` or `false`)
- `APP_URL`: Application URL
- `DB_CONNECTION`: Database connection (`mysql`)
- `DB_HOST`: Database host
- `DB_PORT`: Database port
- `DB_DATABASE`: Database name
- `DB_USERNAME`: Database username
- `DB_PASSWORD`: Database password
- Other variables for logging, caching, sessions, mail, AWS, etc.

## License

This project is licensed under the [MIT License](LICENSE).
