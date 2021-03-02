## Installation Process:
- laravel new `<project_name>`
- composer require `laravel/ui`
- `php artisan ui bootstrap --auth`
- `npm install && npm run dev`


## Package reference:
- https://github.com/laravel/ui
- https://www.youtube.com/watch?v=NuGBzmHlINQ&ab_channel=LaravelDaily


## Other commands: 

Generate basic scaffolding
- php artisan ui bootstrap
- php artisan ui vue
- php artisan ui react

Generate login registration scaffolding
- php artisan ui bootstrap --auth
- php artisan ui vue --auth
- php artisan ui react --auth

Note: This legacy package is a very simple authentication scaffolding built on the Bootstrap CSS framework. While it continues to work with the latest version of Laravel, you should consider using Laravel Breeze for new projects. Or, for something more robust, consider Laravel Jetstream.
