# evervolt.PricesApi

All URIs are relative to *https://api.evervolt.nl*

Method | HTTP request | Description
------------- | ------------- | -------------
[**energy_prices_post**](PricesApi.md#energy_prices_post) | **POST** /energy/prices | Electricity prices
[**energy_schedule_post**](PricesApi.md#energy_schedule_post) | **POST** /energy/schedule | Optimal schedule
[**energy_starttime_post**](PricesApi.md#energy_starttime_post) | **POST** /energy/starttime | Optimal start time


# **energy_prices_post**
> List[ScheduleSlot] energy_prices_post(energy_prices_post_request=energy_prices_post_request)

Electricity prices

This endpoint is used to retrieve current or historical electricity prices

### Example

* Api Key Authentication (ApiKey):

```python
import evervolt
from evervolt.models.energy_prices_post_request import EnergyPricesPostRequest
from evervolt.models.schedule_slot import ScheduleSlot
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
with evervolt.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = evervolt.PricesApi(api_client)
    energy_prices_post_request = evervolt.EnergyPricesPostRequest() # EnergyPricesPostRequest |  (optional)

    try:
        # Electricity prices
        api_response = api_instance.energy_prices_post(energy_prices_post_request=energy_prices_post_request)
        print("The response of PricesApi->energy_prices_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PricesApi->energy_prices_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **energy_prices_post_request** | [**EnergyPricesPostRequest**](EnergyPricesPostRequest.md)|  | [optional] 

### Return type

[**List[ScheduleSlot]**](ScheduleSlot.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved electricity prices |  -  |
**404** | Electricity prices could not be found due to one of the following reasons: - The given provider does not exist ([See all supported providers](/docs/category/aanbieders)) - No market price data is available for (part of) the requested range - No purchasing fee data is available for (part of) the requested range - No tax data is available for (part of) the requested range - No vat data is available for (part of) the requested range  The response body will contain more information on the exact reason  |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **energy_schedule_post**
> List[ScheduleSlot] energy_schedule_post(energy_schedule_post_request=energy_schedule_post_request)

Optimal schedule

This endpoint is used to calculate the optimal schedule for a device based on the electricity prices

### Example

* Api Key Authentication (ApiKey):

```python
import evervolt
from evervolt.models.energy_schedule_post_request import EnergySchedulePostRequest
from evervolt.models.schedule_slot import ScheduleSlot
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
with evervolt.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = evervolt.PricesApi(api_client)
    energy_schedule_post_request = evervolt.EnergySchedulePostRequest() # EnergySchedulePostRequest |  (optional)

    try:
        # Optimal schedule
        api_response = api_instance.energy_schedule_post(energy_schedule_post_request=energy_schedule_post_request)
        print("The response of PricesApi->energy_schedule_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PricesApi->energy_schedule_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **energy_schedule_post_request** | [**EnergySchedulePostRequest**](EnergySchedulePostRequest.md)|  | [optional] 

### Return type

[**List[ScheduleSlot]**](ScheduleSlot.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved optimal schedule |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **energy_starttime_post**
> InlineObject2 energy_starttime_post(energy_starttime_post_request=energy_starttime_post_request)

Optimal start time

This endpoint is used to calculate the optimal start time for a device based on its usage pattern

### Example

* Api Key Authentication (ApiKey):

```python
import evervolt
from evervolt.models.energy_starttime_post_request import EnergyStarttimePostRequest
from evervolt.models.inline_object2 import InlineObject2
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
with evervolt.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = evervolt.PricesApi(api_client)
    energy_starttime_post_request = evervolt.EnergyStarttimePostRequest() # EnergyStarttimePostRequest |  (optional)

    try:
        # Optimal start time
        api_response = api_instance.energy_starttime_post(energy_starttime_post_request=energy_starttime_post_request)
        print("The response of PricesApi->energy_starttime_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling PricesApi->energy_starttime_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **energy_starttime_post_request** | [**EnergyStarttimePostRequest**](EnergyStarttimePostRequest.md)|  | [optional] 

### Return type

[**InlineObject2**](InlineObject2.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Successfully retrieved optimal starting time |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

