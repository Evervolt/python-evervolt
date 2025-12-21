# EnergyStarttimePostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**usage_profile** | [**List[UsageProfileInner]**](UsageProfileInner.md) |  | [optional] 

## Example

```python
from evervolt.models.energy_starttime_post_request import EnergyStarttimePostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of EnergyStarttimePostRequest from a JSON string
energy_starttime_post_request_instance = EnergyStarttimePostRequest.from_json(json)
# print the JSON string representation of the object
print(EnergyStarttimePostRequest.to_json())

# convert the object into a dict
energy_starttime_post_request_dict = energy_starttime_post_request_instance.to_dict()
# create an instance of EnergyStarttimePostRequest from a dict
energy_starttime_post_request_from_dict = EnergyStarttimePostRequest.from_dict(energy_starttime_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


