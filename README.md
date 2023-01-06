# lumen-sail
Installing Laravel Sail Package in Lumen

## Lumen 5.5 acima -> "^5.5|^6.0|^7.0"

`composer require lucenarenato/lumen-sail`

Add this line to bootstrap/app.php

`$app->register(lucenarenato\LumenSail\LumenSailServiceProvider::class);`

## Official Documentation

Documentation for Sail can be found on the [Laravel website](https://laravel.com/docs/sail).

## License

Laravel Sail is open-sourced software licensed under the [MIT license](LICENSE.md).

- Renato Lucena [developer](https://renatolucena.net/) 