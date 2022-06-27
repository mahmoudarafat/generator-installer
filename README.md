# LARAVEL GENERATOR 

https://packagist.org/packages/albadrsystems/laravel-crud-generator

# require laravel 9

## how to install
RUN
` composer require albadrsystems/laravel-crud-generator `

then
` php artisan vendor:publish ` // 0 => for all

then
` php artisan ui stisla --auth `

then 
` npm install `
and
` npm run dev `

then
` php artisan albadrsystems:publish `

then
` php artisan albadrsystems.publish:generator-builder `

then 
` php artisan albadrsystems.publish:layout ` // accept changes

very important
===========
import files from https://github.com/mahmoudarafat/helper-trait and paste it in app folder [ app/Traits/RepositoryTrait.php ]


if you got error in RouteServiceProvider.php 
open it and remove lines added - it may duplicated after namespace App\Providers;
