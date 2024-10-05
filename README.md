# Laravel 11 Template with Breeze, Livewire & Filament

This repository provides a base template for starting a Laravel 11 project, including authentication with Breeze, dynamic components with Livewire, and an admin panel powered by Filament. The setup is designed to streamline the development of web applications with an intuitive and modular structure.

## Features

- **Laravel 11**: Latest version of Laravel, a PHP framework for building modern web applications.
- **Breeze**: Simple, minimal authentication scaffold for Laravel.
- **Livewire**: Full-stack framework for Laravel that makes building dynamic interfaces simple, without leaving the comfort of Laravel.
- **Filament**: Admin panel and form builder for managing your application's resources.

## Getting Started

To get started with this template, follow the instructions below:

### Requirements

- PHP >= 8.2
- Composer
- Node.js & npm
- MySQL or other supported database

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/laravel-template.git
    cd laravel-template
    ```

2. Install PHP dependencies using Composer:

    ```bash
    composer install
    ```

3. Install JavaScript dependencies:

    ```bash
    npm install && npm run dev
    ```

4. Set up the environment variables:

    ```bash
    cp .env.example .env
    php artisan key:generate
    ```

5. Run the migrations to set up the database:

    ```bash
    php artisan migrate
    ```

6. Serve the application:

    ```bash
    php artisan serve
    ```

### Breeze Setup

Breeze provides a simple authentication scaffolding for your Laravel app. It comes pre-configured in this template, but for more customizations, refer to the official documentation:

- [Laravel Breeze Documentation](https://laravel.com/docs/11.x/starter-kits#laravel-breeze)

### Livewire Integration

Livewire is already integrated for building dynamic user interfaces without writing custom JavaScript. Components can be created using Livewire's artisan commands.

- [Livewire Documentation](https://livewire.laravel.com/docs/quickstart)

### Filament Admin Panel

Filament provides an elegant admin interface and form builder for managing your application's resources. This template includes Filament pre-configured for easy extension.

- [Filament Documentation](https://filamentphp.com/docs/3.x/panels/installation)

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. Contributions are welcome!

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE License. See the [LICENSE](LICENSE) file for details.

## Resources

- [Laravel Documentation](https://laravel.com/docs/11.x)
- [Breeze Documentation](https://laravel.com/docs/11.x/starter-kits#laravel-breeze)
- [Livewire Documentation](https://livewire.laravel.com/docs/quickstart)
- [Filament Documentation](https://filamentphp.com/docs/3.x/panels/installation)
