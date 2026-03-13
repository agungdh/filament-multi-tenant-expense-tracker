# Filament Multi-Tenant Expense Tracker

A multi-tenant expense tracker built with Laravel 12 and Filament v5.

## Tech Stack

- **PHP** 8.5
- **Laravel** 12
- **Filament** v5
- **Livewire** v4
- **TailwindCSS** v4
- **PostgreSQL** 18
- **ValKey** 8

## Getting Started

```bash
# Install dependencies
composer install
npm install

# Setup environment
cp .env.example .env
php artisan key:generate

# Run migrations
php artisan migrate

# Start development server
php artisan serve
npm run dev
```

## Code Quality

```bash
# Run Pint (PHP formatter)
vendor/bin/pint

# Check Blade formatting
npm run lint:blade

# Fix Blade formatting
npm run lint:fix:blade

# Run tests
php artisan test
```

## CI/CD

- **Tests**: GitHub Actions with PostgreSQL 18 and ValKey 8
- **Code Quality**: Pint + blade-formatter

## License

MIT
