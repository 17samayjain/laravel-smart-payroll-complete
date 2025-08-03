# Smart Payroll Calculation System - Laravel API

This Laravel 10 API project calculates salaries for different employee types (monthly, daily, hourly), with full attendance-based logic and API access.

## Setup Instructions

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
```

## API Endpoint

`GET /api/salary/{employee_id}?month=YYYY-MM`
