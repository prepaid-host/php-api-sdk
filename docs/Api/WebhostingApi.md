# Swagger\Client\WebhostingApi

All URIs are relative to *https://prepaid-host.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**webhostingIdGet**](WebhostingApi.md#webhostingidget) | **GET** /webhosting/{id} | Gibt das aktuelle Webhosting aus
[**webhostingListGet**](WebhostingApi.md#webhostinglistget) | **GET** /webhosting/list | Gibt eine Liste der aktuellen Webhosting(s) zurück

# **webhostingIdGet**
> \Swagger\Client\Model\InlineResponse20012 webhostingIdGet($api_token)

Gibt das aktuelle Webhosting aus

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\WebhostingApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->webhostingIdGet($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling WebhostingApi->webhostingIdGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |

### Return type

[**\Swagger\Client\Model\InlineResponse20012**](../Model/InlineResponse20012.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **webhostingListGet**
> \Swagger\Client\Model\InlineResponse20011 webhostingListGet($api_token)

Gibt eine Liste der aktuellen Webhosting(s) zurück

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\WebhostingApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->webhostingListGet($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling WebhostingApi->webhostingListGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |

### Return type

[**\Swagger\Client\Model\InlineResponse20011**](../Model/InlineResponse20011.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

