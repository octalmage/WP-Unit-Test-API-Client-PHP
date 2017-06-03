# WP-Unit-Test-API-Client-PHP
#### An API to collect unit test results.

This PHP package is automatically generated by the [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) project:

- API version: 1.0.0
- Build package: io.swagger.codegen.languages.PhpClientCodegen

## Requirements

PHP 5.4.0 and later

## Installation & Usage
### Composer

To install the bindings via [Composer](http://getcomposer.org/), add the following to `composer.json`:

```
{
  "repositories": [
    {
      "type": "git",
      "url": "https://github.com/octalmage/WPUnitTestAPI.git"
    }
  ],
  "require": {
    "octalmage/WPUnitTestAPI": "*@dev"
  }
}
```

Then run `composer install`

### Manual Installation

Download the files and include `autoload.php`:

```php
    require_once('/path/to/WP-Unit-Test-API-Client-PHP/autoload.php');
```

## Tests

To run the unit tests:

```
composer install
./vendor/bin/phpunit
```

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new octalmage\WPUnitTestAPI\Api\DefaultApi();
$results = new \octalmage\WPUnitTestAPI\Model\NewResult(); // \octalmage\WPUnitTestAPI\Model\NewResult | Results to submit.

try {
    $result = $api_instance->addResults($results);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->addResults: ', $e->getMessage(), PHP_EOL;
}

?>
```

## Documentation for API Endpoints

All URIs are relative to *http://localhost:8087/wp-json/wp-unit-test-api/v1*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*DefaultApi* | [**addResults**](docs/Api/DefaultApi.md#addresults) | **POST** /results | 


## Documentation For Models

 - [Error](docs/Model/Error.md)
 - [ErrorData](docs/Model/ErrorData.md)
 - [NewResult](docs/Model/NewResult.md)
 - [Response](docs/Model/Response.md)


## Documentation For Authorization

 All endpoints do not require authorization.


## Author




