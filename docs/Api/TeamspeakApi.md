# Swagger\Client\TeamspeakApi

All URIs are relative to *https://prepaid-host.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**teamspeakIdGet**](TeamspeakApi.md#teamspeakidget) | **GET** /teamspeak/{id} | Gibt Details eines TeamSpeak Servers aus
[**teamspeakIdStartPost**](TeamspeakApi.md#teamspeakidstartpost) | **POST** /teamspeak/{id}/start | Startet den gewünschten Teamspeak Server
[**teamspeakIdStopPost**](TeamspeakApi.md#teamspeakidstoppost) | **POST** /teamspeak/{id}/stop | Stoppt den gewünschten Teamspeak Server
[**teamspeakListGet**](TeamspeakApi.md#teamspeaklistget) | **GET** /teamspeak/list | Gibt eine Liste der aktuellen TeamSpeak Server zurück

# **teamspeakIdGet**
> \Swagger\Client\Model\InlineResponse20010 teamspeakIdGet($api_token)

Gibt Details eines TeamSpeak Servers aus

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\TeamspeakApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->teamspeakIdGet($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling TeamspeakApi->teamspeakIdGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |

### Return type

[**\Swagger\Client\Model\InlineResponse20010**](../Model/InlineResponse20010.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **teamspeakIdStartPost**
> \Swagger\Client\Model\InlineResponse2008 teamspeakIdStartPost($api_token)

Startet den gewünschten Teamspeak Server

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\TeamspeakApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->teamspeakIdStartPost($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling TeamspeakApi->teamspeakIdStartPost: ', $e->getMessage(), PHP_EOL;
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

# **teamspeakIdStopPost**
> \Swagger\Client\Model\InlineResponse2008 teamspeakIdStopPost($api_token)

Stoppt den gewünschten Teamspeak Server

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\TeamspeakApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->teamspeakIdStopPost($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling TeamspeakApi->teamspeakIdStopPost: ', $e->getMessage(), PHP_EOL;
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

# **teamspeakListGet**
> \Swagger\Client\Model\InlineResponse200 teamspeakListGet($api_token)

Gibt eine Liste der aktuellen TeamSpeak Server zurück

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\TeamspeakApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->teamspeakListGet($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling TeamspeakApi->teamspeakListGet: ', $e->getMessage(), PHP_EOL;
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

