<h1 align="center">Registry Component</h1>

<p align="center">
Registry component provides a mechanism for storing data globally in a well managed fashion, helping to prevent global meltdown.
</p>

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
use Flextype\Component\Registry;

$registry = new Registry();
```

### Methods

| Method | Description |
|---|---|
| <a href="#registry_set">`set()`</a> | |
| <a href="#registry_get">`get()`</a> | |
| <a href="#registry_has">`has()`</a> | |
| <a href="#registry_delete">`delete()`</a> | |
| <a href="#registry_flush">`flush()`</a> | |
| <a href="#registry_all">`all()`</a> | |

<hr>

#### <a name="registry_set"></a> Method: `set()`

```php
$registry->set('movies.the-thin-red-line.title', 'The Thin Red Line');
```

### License
[The MIT License (MIT)](https://github.com/flextype-components/registry/blob/master/LICENSE.txt)
Copyright (c) 2020 [Sergey Romanenko](https://github.com/Awilum)
