# octalmage\WPUnitTestAPI\DefaultApi

All URIs are relative to *http://https://wpunittestapi.wpengine.com/wp-json/wp-unit-test-api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**addResults**](DefaultApi.md#addResults) | **POST** /results | 


# **addResults**
> \octalmage\WPUnitTestAPI\Model\Response addResults($results)



Creates a new results post.

### Example
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

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **results** | [**\octalmage\WPUnitTestAPI\Model\NewResult**](../Model/\octalmage\WPUnitTestAPI\Model\NewResult.md)| Results to submit. |

### Return type

[**\octalmage\WPUnitTestAPI\Model\Response**](../Model/Response.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

