# Laravel E-Commerce Project

This is a simple e-commerce web application built with Laravel, featuring product management, user authentication, and a shopping cart system.

## Features

- User authentication (registration, login, and logout).
- Product listing with detailed descriptions and pricing.
- Individual product pages.
- Add and remove items from the shopping cart.
- View cart summary, including subtotal.

## Requirements

- PHP >= 8.0
- Composer
- Laravel 10
- Node.js and npm (for frontend assets)
- A database (SQLite, MySQL, PostgreSQL, etc.)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/adr-1an/online-shopping
   cd online-shopping
   ```
2. Install dependencies:
    ```bash
    composer install
    npm install
    ```
3. Set up your .env file:
   ```bash
   cp .env.example .env
   ```
   Configure database settings in .env.

4. Generate the application key:
   ```bash
   php artisan key:generate
   ```
5. Run migrations:
   ```bash
   php artisan migrate
   ```
6. Serve the application:
   ```bash
   php artisan serve
   npm run dev
   ```
   Note: Keep both commands running at the same time, or CSS won't work.


## Usage:

1. Open the application in your browser. By default, it's at
```bash
http://localhost:8000
```

2. Click "Register" on the top right corner and register.

**Done!**
