# EnergyPricesPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**start** | **datetime** | Defaults to the current time, rounded down to the beginning of the nearest defined interval (e.g., if the interval is 1 hour, it defaults to the last full hour). | [optional] 
**end** | **datetime** | Defaults to 24 hours in the future, rounded up to the beginning of the nearest defined interval (e.g., if the interval is 1 hour, it defaults to the next full hour). | [optional] 
**provider** | [**Providers**](Providers.md) |  | [optional] 
**include_tax** | **bool** | Whether to include tax in the returned prices | [optional] 

## Example

```python
from evervolt.models.energy_prices_post_request import EnergyPricesPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of EnergyPricesPostRequest from a JSON string
energy_prices_post_request_instance = EnergyPricesPostRequest.from_json(json)
# print the JSON string representation of the object
print(EnergyPricesPostRequest.to_json())

# convert the object into a dict
energy_prices_post_request_dict = energy_prices_post_request_instance.to_dict()
# create an instance of EnergyPricesPostRequest from a dict
energy_prices_post_request_from_dict = EnergyPricesPostRequest.from_dict(energy_prices_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


