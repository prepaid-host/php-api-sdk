# Swagger\Client\PaymentApi

All URIs are relative to *https://prepaid-host.com/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**paymentGet**](PaymentApi.md#paymentget) | **GET** /payment | Gibt zu einer Transaktion ein Status aus
[**paymentPost**](PaymentApi.md#paymentpost) | **POST** /payment | Erstellt eine Zahlung

# **paymentGet**
> \Swagger\Client\Model\InlineResponse2005 paymentGet($api_token, $cid)

Gibt zu einer Transaktion ein Status aus

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\PaymentApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token
$cid = "cid_example"; // string | Transaktions ID

try {
    $result = $apiInstance->paymentGet($api_token, $cid);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PaymentApi->paymentGet: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |
 **cid** | **string**| Transaktions ID |

### Return type

[**\Swagger\Client\Model\InlineResponse2005**](../Model/InlineResponse2005.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

# **paymentPost**
> \Swagger\Client\Model\InlineResponse2006 paymentPost($api_token, $amount, $payment_method, $ok_url, $nok_url, $pn_url, $reason)

Erstellt eine Zahlung

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new Swagger\Client\Api\PaymentApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$api_token = "api_token_example"; // string | API Token
$amount = "amount_example"; // string | Wert der Transaktion
$payment_method = "payment_method_example"; // string | Zahlungsmethode(PAYPAL,PAYSAFECARD)
$ok_url = "ok_url_example"; // string | Erfolgreiche URL
$nok_url = "nok_url_example"; // string | Nict erfolgreiche URL
$pn_url = "pn_url_example"; // string | PN URL
$reason = "reason_example"; // string | Grund für die Transaktion

try {
    $result = $apiInstance->paymentPost($api_token, $amount, $payment_method, $ok_url, $nok_url, $pn_url, $reason);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling PaymentApi->paymentPost: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **api_token** | **string**| API Token |
 **amount** | **string**| Wert der Transaktion |
 **payment_method** | **string**| Zahlungsmethode(PAYPAL,PAYSAFECARD) |
 **ok_url** | **string**| Erfolgreiche URL |
 **nok_url** | **string**| Nict erfolgreiche URL |
 **pn_url** | **string**| PN URL |
 **reason** | **string**| Grund für die Transaktion |

### Return type

[**\Swagger\Client\Model\InlineResponse2006**](../Model/InlineResponse2006.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

