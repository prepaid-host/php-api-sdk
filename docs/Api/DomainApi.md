# Swagger\Client\DomainApi

All URIs are relative to *https://prepaid-host.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**domainIdAddPost**](DomainApi.md#domainidaddpost) | **POST** /domain/{id}/add | Fügt ein DNS Eintag zu der Domain hinzu
[**domainIdDNSGet**](DomainApi.md#domainiddnsget) | **GET** /domain/{id}/DNS | Gibt eine Liste der aktuellen DNS Einträge der Domain zurück
[**domainIdDeleteDelete**](DomainApi.md#domainiddeletedelete) | **DELETE** /domain/{id}/delete | Löscht ein DNS Eintag zu der Domain hinzu
[**domainIdGet**](DomainApi.md#domainidget) | **GET** /domain/{id} | Gibt Infos zu einer Domain aus
[**domainListGet**](DomainApi.md#domainlistget) | **GET** /domain/list | Gibt eine Liste der aktuellen Domains zurück

# **domainIdAddPost**
> \Swagger\Client\Model\InlineResponse2004 domainIdAddPost($api_token, $sld, $type, $data)

Fügt ein DNS Eintag zu der Domain hinzu

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DomainApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token
$sld = "sld_example"; // string | Subdomain der Domain
$type = "type_example"; // string | Typ der SLD(A|AAAA|CNAME|MX|SRV|TXT|PTR|HTTP_FRAME|HTTP_REDIRECT)
$data = "data_example"; // string | Ziel der SLD

try {
    $result = $apiInstance->domainIdAddPost($api_token, $sld, $type, $data);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DomainApi->domainIdAddPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |
 **sld** | **string**| Subdomain der Domain |
 **type** | **string**| Typ der SLD(A|AAAA|CNAME|MX|SRV|TXT|PTR|HTTP_FRAME|HTTP_REDIRECT) |
 **data** | **string**| Ziel der SLD |

### Return type

[**\Swagger\Client\Model\InlineResponse2004**](../Model/InlineResponse2004.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **domainIdDNSGet**
> \Swagger\Client\Model\InlineResponse2003 domainIdDNSGet($api_token)

Gibt eine Liste der aktuellen DNS Einträge der Domain zurück

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DomainApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->domainIdDNSGet($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DomainApi->domainIdDNSGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |

### Return type

[**\Swagger\Client\Model\InlineResponse2003**](../Model/InlineResponse2003.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **domainIdDeleteDelete**
> \Swagger\Client\Model\InlineResponse2003 domainIdDeleteDelete($api_token, $sld, $type, $data)

Löscht ein DNS Eintag zu der Domain hinzu

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DomainApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token
$sld = "sld_example"; // string | Subdomain der Domain
$type = "type_example"; // string | Typ der SLD(A|AAAA|CNAME|MX|SRV|TXT|PTR|HTTP_FRAME|HTTP_REDIRECT)
$data = "data_example"; // string | Ziel der SLD

try {
    $result = $apiInstance->domainIdDeleteDelete($api_token, $sld, $type, $data);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DomainApi->domainIdDeleteDelete: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |
 **sld** | **string**| Subdomain der Domain |
 **type** | **string**| Typ der SLD(A|AAAA|CNAME|MX|SRV|TXT|PTR|HTTP_FRAME|HTTP_REDIRECT) |
 **data** | **string**| Ziel der SLD |

### Return type

[**\Swagger\Client\Model\InlineResponse2003**](../Model/InlineResponse2003.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **domainIdGet**
> \Swagger\Client\Model\InlineResponse2002 domainIdGet($api_token)

Gibt Infos zu einer Domain aus

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DomainApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->domainIdGet($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DomainApi->domainIdGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |

### Return type

[**\Swagger\Client\Model\InlineResponse2002**](../Model/InlineResponse2002.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **domainListGet**
> \Swagger\Client\Model\InlineResponse2001 domainListGet($api_token)

Gibt eine Liste der aktuellen Domains zurück

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\DomainApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token

try {
    $result = $apiInstance->domainListGet($api_token);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DomainApi->domainListGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |

### Return type

[**\Swagger\Client\Model\InlineResponse2001**](../Model/InlineResponse2001.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

