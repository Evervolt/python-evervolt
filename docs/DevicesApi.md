# evervolt.DevicesApi

All URIs are relative to *https://api.evervolt.beestree.nl*

Method | HTTP request | Description
------------- | ------------- | -------------
[**devices_delete**](DevicesApi.md#devices_delete) | **DELETE** /devices | Delete device
[**devices_get**](DevicesApi.md#devices_get) | **GET** /devices | Get devices
[**devices_post**](DevicesApi.md#devices_post) | **POST** /devices | Add device


# **devices_delete**
> devices_delete(devices_delete_request=devices_delete_request)

Delete device

This endpoint is used to delete a device

### Example

* Api Key Authentication (ApiKey):

```python
import evervolt
from evervolt.models.devices_delete_request import DevicesDeleteRequest
from evervolt.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.evervolt.beestree.nl
# See configuration.py for a list of all supported configuration parameters.
configuration = evervolt.Configuration(
    host = "https://api.evervolt.beestree.nl"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: ApiKey
configuration.api_key['ApiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['ApiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with evervolt.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = evervolt.DevicesApi(api_client)
    devices_delete_request = evervolt.DevicesDeleteRequest() # DevicesDeleteRequest |  (optional)

    try:
        # Delete device
        api_instance.devices_delete(devices_delete_request=devices_delete_request)
    except Exception as e:
        print("Exception when calling DevicesApi->devices_delete: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **devices_delete_request** | [**DevicesDeleteRequest**](DevicesDeleteRequest.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully deleted the device |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **devices_get**
> List[InlineObject1Inner] devices_get()

Get devices

This endpoint is used to get all devices

### Example

* Api Key Authentication (ApiKey):

```python
import evervolt
from evervolt.models.inline_object1_inner import InlineObject1Inner
from evervolt.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.evervolt.beestree.nl
# See configuration.py for a list of all supported configuration parameters.
configuration = evervolt.Configuration(
    host = "https://api.evervolt.beestree.nl"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: ApiKey
configuration.api_key['ApiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['ApiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with evervolt.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = evervolt.DevicesApi(api_client)

    try:
        # Get devices
        api_response = api_instance.devices_get()
        print("The response of DevicesApi->devices_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling DevicesApi->devices_get: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**List[InlineObject1Inner]**](InlineObject1Inner.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved devices |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **devices_post**
> devices_post(devices_post_request=devices_post_request)

Add device

This endpoint is used to add a new device

### Example

* Api Key Authentication (ApiKey):

```python
import evervolt
from evervolt.models.devices_post_request import DevicesPostRequest
from evervolt.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.evervolt.beestree.nl
# See configuration.py for a list of all supported configuration parameters.
configuration = evervolt.Configuration(
    host = "https://api.evervolt.beestree.nl"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: ApiKey
configuration.api_key['ApiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['ApiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with evervolt.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = evervolt.DevicesApi(api_client)
    devices_post_request = evervolt.DevicesPostRequest() # DevicesPostRequest |  (optional)

    try:
        # Add device
        api_instance.devices_post(devices_post_request=devices_post_request)
    except Exception as e:
        print("Exception when calling DevicesApi->devices_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **devices_post_request** | [**DevicesPostRequest**](DevicesPostRequest.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully added the new device |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

