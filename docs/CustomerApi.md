# evervolt.CustomerApi

All URIs are relative to *https://api.evervolt.nl*

Method | HTTP request | Description
------------- | ------------- | -------------
[**customer_get**](CustomerApi.md#customer_get) | **GET** /customer | Get customer


# **customer_get**
> InlineObject customer_get()

Get customer

This endpoint is used to get information about the customer

### Example

* Api Key Authentication (ApiKey):

```python
import evervolt
from evervolt.models.inline_object import InlineObject
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
    api_instance = evervolt.CustomerApi(api_client)

    try:
        # Get customer
        api_response = await api_instance.customer_get()
        print("The response of CustomerApi->customer_get:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CustomerApi->customer_get: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

[**InlineObject**](InlineObject.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved customer |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

