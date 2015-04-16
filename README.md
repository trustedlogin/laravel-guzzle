# Laravel - Guzzle 5 Service Provider
[![Stable Status](https://poser.pugx.org/urakozz/laravel-guzzle/v/stable.png)](https://packagist.org/packages/kozz/laravel-guzzle-provider)

laravel guzzle service provider

## Install With Composer:

```json
"require": {
    "kozz/laravel-guzzle": "~1.0"
}
```

## Register Service Provider

*/configs/app.php*

```php
    ...
    'providers' => [

        /*
         * Laravel Framework Service Providers...
         */
        ...

        /*
         * Application Service Providers...
         */
        ...
        'Kozz\Laravel\Providers\Guzzle'
    ],
```
