[![Build Status](https://travis-ci.org/thomaswelton/laravel-facebook.png?branch=master)](https://travis-ci.org/thomaswelton/laravel-facebook)
[![Latest Stable Version](https://poser.pugx.org/thomaswelton/laravel-facebook/v/stable.png)](https://packagist.org/packages/thomaswelton/laravel-facebook)
[![Total Downloads](https://poser.pugx.org/thomaswelton/laravel-facebook/downloads.png)](https://packagist.org/packages/thomaswelton/laravel-facebook)


# Installation

Update your `composer.json` file to include this package as a dependency
```json
"thomaswelton/laravel-google-analytics": "dev-master"
```

Register the Facebook service provider by adding it to the providers array in the `app/config/app.php` file. 
```
Thomaswelton\LaravelGoogleAnalytics\LaravelGoogleAnalyticsServiceProvider
```

Alias the Facebook facade by adding it to the aliases array in the `app/config/app.php` file. 
```php
'aliases' => array(
	'GoogleAnalytics' => 'Thomaswelton\LaravelGoogleAnalytics\Facades\GoogleAnalytics'
)
```

# Configuration

Copy the config file into your project by running
```
php artisan config:publish thomaswelton/laravel-google-analytics"
```

Edit the config file to include your account ID
