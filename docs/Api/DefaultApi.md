# octalmage\wp-unit-test-api\DefaultApi

All URIs are relative to *https://wpunittestapi.wpengine.com/wp-json/wp-unit-test-api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addResults**](DefaultApi.md#addResults) | **POST** /results | 


# **addResults**
> \octalmage\wp-unit-test-api\Model\Response addResults($results)



Creates a new results post.

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new octalmage\wp-unit-test-api\Api\DefaultApi();
$results = new \octalmage\wp-unit-test-api\Model\NewResult(); // \octalmage\wp-unit-test-api\Model\NewResult | Results to submit.

try {
    $result = $api_instance->addResults($results);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->addResults: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **results** | [**\octalmage\wp-unit-test-api\Model\NewResult**](../Model/\octalmage\wp-unit-test-api\Model\NewResult.md)| Results to submit. |

### Return type

[**\octalmage\wp-unit-test-api\Model\Response**](../Model/Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

