# evervolt.ProvidersApi

All URIs are relative to *https://api.evervolt.nl*

Method | HTTP request | Description
------------- | ------------- | -------------
[**providers_get**](ProvidersApi.md#providers_get) | **GET** /providers | Get providers


# **providers_get**
> List[InlineObject3Inner] providers_get()

Get providers

This endpoint is used to list all supported providers

### Example

* Api Key Authentication (ApiKey):

```python
import evervolt
from evervolt.models.inline_object3_inner import InlineObject3Inner
from evervolt.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.evervolt.nl
# See configuration.py for a list of all supported configuration parameters.
configuration = evervolt.Configuration(
    host = "https://api.evervolt.nl"
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
async with evervolt.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = evervolt.ProvidersApi(api_client)

    try:
        # Get providers
        api_response = await api_instance.providers_get()
        print("The response of ProvidersApi->providers_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ProvidersApi->providers_get: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**List[InlineObject3Inner]**](InlineObject3Inner.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved providers |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

