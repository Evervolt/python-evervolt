# evervolt.DefaultApi

All URIs are relative to *https://api.evervolt.beestree.nl*

Method | HTTP request | Description
------------- | ------------- | -------------
[**devices_delete**](DefaultApi.md#devices_delete) | **DELETE** /devices | 
[**devices_get**](DefaultApi.md#devices_get) | **GET** /devices | 
[**devices_post**](DefaultApi.md#devices_post) | **POST** /devices | 
[**energy_prices_post**](DefaultApi.md#energy_prices_post) | **POST** /energy/prices | 
[**energy_schedule_post**](DefaultApi.md#energy_schedule_post) | **POST** /energy/schedule | 
[**energy_starttime_post**](DefaultApi.md#energy_starttime_post) | **POST** /energy/starttime | 


# **devices_delete**
> devices_delete()

### Example


```python
import evervolt
from evervolt.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.evervolt.beestree.nl
# See configuration.py for a list of all supported configuration parameters.
configuration = evervolt.Configuration(
    host = "https://api.evervolt.beestree.nl"
)


# Enter a context with an instance of the API client
with evervolt.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = evervolt.DefaultApi(api_client)

    try:
        api_instance.devices_delete()
    except Exception as e:
        print("Exception when calling DefaultApi->devices_delete: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined


[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **devices_get**
> devices_get()

### Example


```python
import evervolt
from evervolt.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.evervolt.beestree.nl
# See configuration.py for a list of all supported configuration parameters.
configuration = evervolt.Configuration(
    host = "https://api.evervolt.beestree.nl"
)


# Enter a context with an instance of the API client
with evervolt.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = evervolt.DefaultApi(api_client)

    try:
        api_instance.devices_get()
    except Exception as e:
        print("Exception when calling DefaultApi->devices_get: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined


[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **devices_post**
> devices_post()

### Example


```python
import evervolt
from evervolt.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.evervolt.beestree.nl
# See configuration.py for a list of all supported configuration parameters.
configuration = evervolt.Configuration(
    host = "https://api.evervolt.beestree.nl"
)


# Enter a context with an instance of the API client
with evervolt.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = evervolt.DefaultApi(api_client)

    try:
        api_instance.devices_post()
    except Exception as e:
        print("Exception when calling DefaultApi->devices_post: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined


[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **energy_prices_post**
> energy_prices_post()

### Example


```python
import evervolt
from evervolt.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.evervolt.beestree.nl
# See configuration.py for a list of all supported configuration parameters.
configuration = evervolt.Configuration(
    host = "https://api.evervolt.beestree.nl"
)


# Enter a context with an instance of the API client
with evervolt.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = evervolt.DefaultApi(api_client)

    try:
        api_instance.energy_prices_post()
    except Exception as e:
        print("Exception when calling DefaultApi->energy_prices_post: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined


[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **energy_schedule_post**
> energy_schedule_post()

### Example


```python
import evervolt
from evervolt.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.evervolt.beestree.nl
# See configuration.py for a list of all supported configuration parameters.
configuration = evervolt.Configuration(
    host = "https://api.evervolt.beestree.nl"
)


# Enter a context with an instance of the API client
with evervolt.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = evervolt.DefaultApi(api_client)

    try:
        api_instance.energy_schedule_post()
    except Exception as e:
        print("Exception when calling DefaultApi->energy_schedule_post: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined


[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **energy_starttime_post**
> energy_starttime_post()

### Example


```python
import evervolt
from evervolt.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.evervolt.beestree.nl
# See configuration.py for a list of all supported configuration parameters.
configuration = evervolt.Configuration(
    host = "https://api.evervolt.beestree.nl"
)


# Enter a context with an instance of the API client
with evervolt.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = evervolt.DefaultApi(api_client)

    try:
        api_instance.energy_starttime_post()
    except Exception as e:
        print("Exception when calling DefaultApi->energy_starttime_post: %s\n" % e)
```



### Parameters

This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined


[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

