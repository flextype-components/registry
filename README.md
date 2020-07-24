<h1 align="center">Registry Component</h1>

<p align="center">
<a href="https://github.com/flextype-components/registry/releases"><img alt="Version" src="https://img.shields.io/github/release/flextype-components/registry.svg?label=version&color=green"></a> <a href="https://github.com/flextype-components/registry"><img src="https://img.shields.io/badge/license-MIT-blue.svg?color=green" alt="License"></a> <a href="https://github.com/flextype-components/registry"><img src="https://img.shields.io/github/downloads/flextype-components/registry/total.svg?color=green" alt="Total downloads"></a> <a href="https://scrutinizer-ci.com/g/flextype-components/registry?branch=master"><img src="https://img.shields.io/scrutinizer/g/flextype-components/registry.svg?branch=master&color=green" alt="Quality Score"></a>
</p>
<br>

### Installation

With [Composer](https://getcomposer.org):

```
composer require flextype-components/registry
```

### Usage

```php
use Flextype\Component\Arrays;

$registry = new Registry();
```

### Methods

| Method | Description |
|---|---|
| <a href="#array_set">`Arrays::set()`</a> | Set an array item to a given value using "dot" notation. If no key is given to the method, the entire array will be replaced. |
| <a href="#array_get">`Arrays::get()`</a> | Returns value from array using "dot notation". If the key does not exist in the array, the default value will be returned instead. |
| <a href="#array_delete">`Arrays::delete()`</a> | Deletes an array value using "dot notation". |
| <a href="#array_has">`Arrays::has()`</a> | Checks if the given dot-notated key exists in the array. |
| <a href="#array_dot">`Arrays::dot()`</a> | Flatten a multi-dimensional associative array with dots. |
| <a href="#array_undot">`Arrays::undot()`</a> | Expands a dot notation array into a full multi-dimensional array. |

<hr>

#### <a name="array_set"></a> Method: `Arrays::set()`

Set an array item to a given value using "dot" notation. If no key is given to the method, the entire array will be replaced.

```php
Arrays::set($array, 'movies.the-thin-red-line.title', 'The Thin Red Line');
```

### License
[The MIT License (MIT)](https://github.com/flextype-components/registry/blob/master/LICENSE.txt)
Copyright (c) 2020 [Sergey Romanenko](https://github.com/Awilum)
