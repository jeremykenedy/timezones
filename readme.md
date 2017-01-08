# Timezones | A Laravel package - v0.0.5

[![Total Downloads](https://poser.pugx.org/jeremykenedy/timezones/d/total.svg)](https://packagist.org/packages/jeremykenedy/timezones)
[![Latest Stable Version](https://poser.pugx.org/jeremykenedy/timezones/v/stable.svg)](https://packagist.org/packages/jeremykenedy/timezones)
[![License](https://poser.pugx.org/jeremykenedy/timezones/license.svg)](https://packagist.org/packages/jeremykenedy/timezones)

## Introduction

This is a base example of a laravel package. The focus is on the framework of the package and the essential elements and not so much what it actually does. It returns the time and date in a Laravel application when going to the the URL `/timezones/{TIMEZONE}` from the projects base url.

## Installation

1. From your projects root folder in terminal run:

   ```
      composer require jeremykenedy/timeszones
   ```

2. Register the package with laravel in `config/app.php` under the **Application Service Providers** section with the following:

   ```
      jeremykenedy\Timezones\TimezonesServiceProvider::class,
   ```

3. (Optional) Publish the packages assets/views to be customized by running the following from your projects root folder:

   ```
      php artisan publish
   ```

## Usage

```
   http://your-projects-url/timezones/{{TIMEZONE}}
```

#### Usage Examples:

```
   http://lara-timezone.local/timezones/PST
   http://lara-timezone.local/timezones/MST
   http://lara-timezone.local/timezones/CST
   http://lara-timezone.local/timezones/EST
   http://lara-timezone.local/timezones/UTC
```

## License

Timezones - A Laravel package is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
