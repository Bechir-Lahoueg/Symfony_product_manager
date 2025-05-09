# Symfony Product Manager

A web application built with Symfony for managing products and categories.

## Features

- Product management (create, read, update, delete)
- Category management
- Product filtering by name
- Product filtering by category
- Product filtering by price range
- Responsive design with Bootstrap

## Requirements

- PHP 8.2 or higher
- Composer
- PostgreSQL or MySQL database

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/Symfony_product_manager.git
   cd Symfony_product_manager
   ```

2. Install dependencies:
   ```
   composer install
   ```

3. Configure your database in `.env` file:
   ```
   DATABASE_URL="postgresql://app:!ChangeMe!@127.0.0.1:5432/app?serverVersion=16&charset=utf8"
   ```

4. Create database and run migrations:
   ```
   php bin/console doctrine:database:create
   php bin/console doctrine:migrations:migrate
   ```

5. Start the Symfony server:
   ```
   symfony server:start
   ```

6. Access the application at `http://localhost:8000`

## Usage

- Home page: View all products with search functionality
- Add new products: Click "Ajouter article" in the navigation
- Add new categories: Click "Ajouter catégorie" in the navigation
- Filter by category: Click "Recherche par catégorie" in the navigation
- Filter by price: Click "Recherche par prix" in the navigation
