# Country and states using Sushi
Countries and States for Laravel with the missing Sushi array Eloquent driver.

There is a little helper function in Countries that determens if a country is in Europe. I find it usefull for VAT form in checkout forms.
```
$country = Country::first();
$inEurope = $country->inEurope();
```

Dont forget to install the Sushi driver on your laravel project.

https://github.com/calebporzio/sushi

```
composer require calebporzio/sushi
```


