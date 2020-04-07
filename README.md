# Laravel Nova Polygon Map 1:n Field

## Installation
Use composer to install the package.

```shell
composer require genesiscz/laravel-nova-polygon-map-field
```


## Usage

```php 

use Genesiscz\PolygonMap\Polygon;
use Genesiscz\PolygonMap\Point;

Polygon::make('map'),
// or
Point::make('map'),


// env file 
GOOGLE_MAPS_KEY=
```

## License
The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
