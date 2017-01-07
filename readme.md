# Timezones | A Laravel package - v0.0.2

[![Total Downloads](https://poser.pugx.org/jeremykenedy/timezones/d/total.svg)](https://packagist.org/packages/jeremykenedy/timezones)
[![Latest Stable Version](https://poser.pugx.org/jeremykenedy/timezones/v/stable.svg)](https://packagist.org/packages/jeremykenedy/timezones)
[![License](https://poser.pugx.org/jeremykenedy/timezones/license.svg)](https://packagist.org/packages/jeremykenedy/timezones)

## Introduction

This is a base example of a laravel package. The focus is on the framework of the package and the essential elements and not so much what it actually does. It returns the time and date in a Laravel application when going to the the URL `/timezones/{TIMEZONE}` from the projects base url.

## Installation
```
   composer require jeremykenedy/timeszones
```
[packagist](https://packagist.org/packages/jeremykenedy/timezones)

#### Optionally publish assets/views to be customized with
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
