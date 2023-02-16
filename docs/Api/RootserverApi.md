# Swagger\Client\RootserverApi

All URIs are relative to *https://prepaid-host.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**rootserverIdAddressesGet**](RootserverApi.md#rootserveridaddressesget) | **GET** /rootserver/{id}/addresses | Gibt die IP Adressen des Rootservers aus
[**rootserverIdRestartPost**](RootserverApi.md#rootserveridrestartpost) | **POST** /rootserver/{id}/restart | Startet den gewünschten Rootserver neu
[**rootserverIdStartPost**](RootserverApi.md#rootserveridstartpost) | **POST** /rootserver/{id}/start | Startet den gewünschten Rootserver
[**rootserverIdStatsGet**](RootserverApi.md#rootserveridstatsget) | **GET** /rootserver/{id}/stats | Gibt den aktuellen Status der Rootserver durch
[**rootserverIdStopPost**](RootserverApi.md#rootserveridstoppost) | **POST** /rootserver/{id}/stop | Stoppt den gewünschten Rootserver
[**rootserverListGet**](RootserverApi.md#rootserverlistget) | **GET** /rootserver/list | Gibt eine Liste der aktuellen Rootserver zurück

# **rootserverIdAddressesGet**
> \Swagger\Client\Model\InlineResponse2009 rootserverIdAddressesGet($api_token)

Gibt die IP Adressen des Rootservers aus

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\RootserverApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->rootserverIdAddressesGet($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling RootserverApi->rootserverIdAddressesGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |

### Return type

[**\Swagger\Client\Model\InlineResponse2009**](../Model/InlineResponse2009.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **rootserverIdRestartPost**
> \Swagger\Client\Model\InlineResponse2008 rootserverIdRestartPost($api_token)

Startet den gewünschten Rootserver neu

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\RootserverApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->rootserverIdRestartPost($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling RootserverApi->rootserverIdRestartPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |

### Return type

[**\Swagger\Client\Model\InlineResponse2008**](../Model/InlineResponse2008.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **rootserverIdStartPost**
> \Swagger\Client\Model\InlineResponse2008 rootserverIdStartPost($api_token)

Startet den gewünschten Rootserver

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\RootserverApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->rootserverIdStartPost($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling RootserverApi->rootserverIdStartPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |

### Return type

[**\Swagger\Client\Model\InlineResponse2008**](../Model/InlineResponse2008.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **rootserverIdStatsGet**
> \Swagger\Client\Model\InlineResponse2008 rootserverIdStatsGet($api_token)

Gibt den aktuellen Status der Rootserver durch

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\RootserverApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->rootserverIdStatsGet($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling RootserverApi->rootserverIdStatsGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |

### Return type

[**\Swagger\Client\Model\InlineResponse2008**](../Model/InlineResponse2008.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **rootserverIdStopPost**
> \Swagger\Client\Model\InlineResponse2008 rootserverIdStopPost($api_token)

Stoppt den gewünschten Rootserver

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\RootserverApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->rootserverIdStopPost($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling RootserverApi->rootserverIdStopPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |

### Return type

[**\Swagger\Client\Model\InlineResponse2008**](../Model/InlineResponse2008.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **rootserverListGet**
> \Swagger\Client\Model\InlineResponse2007 rootserverListGet($api_token)

Gibt eine Liste der aktuellen Rootserver zurück

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\RootserverApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->rootserverListGet($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling RootserverApi->rootserverListGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |

### Return type

[**\Swagger\Client\Model\InlineResponse2007**](../Model/InlineResponse2007.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

