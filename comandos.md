```
composer create-project laravel/laravel gCalendarLaravel
composer require spatie/laravel-google-calendar
php artisan vendor:publish --provider="Spatie\GoogleCalendar\GoogleCalendarServiceProvider"
composer require google/apiclient
```