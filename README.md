# Searchable select filter for Laravel Nova.

forked from https://github.com/Fontech/nova-searchable-select-filter

## Installation

```bash
composer require codealliance/nova-searchable-select-filter
```

## Usage

Just simply replace filter's component property to `searchable-select-filter`, that's all.

```php
namespace App\Nova\Filters;

use Laravel\Nova\Filters\Filter;

class MyAwesomeFilter extends Filter
{
    public $component = 'searchable-select-filter';
}
```
