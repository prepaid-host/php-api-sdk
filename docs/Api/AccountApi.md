# Swagger\Client\AccountApi

All URIs are relative to *https://prepaid-host.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**accountGet**](AccountApi.md#accountget) | **GET** /account | Gibt alle Account Informationen aus

# **accountGet**
> \Swagger\Client\Model\InlineResponse200 accountGet($api_token)

Gibt alle Account Informationen aus

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\AccountApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->accountGet($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling AccountApi->accountGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |

### Return type

[**\Swagger\Client\Model\InlineResponse200**](../Model/InlineResponse200.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

