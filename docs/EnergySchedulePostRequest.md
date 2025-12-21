# EnergySchedulePostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**start** | **datetime** | Defaults to the current time, rounded down to the beginning of the nearest defined interval (e.g., if the interval is 1 hour, it defaults to the last full hour). | [optional] 
**end** | **datetime** | Defaults to 24 hours in the future, rounded up to the beginning of the nearest defined interval (e.g., if the interval is 1 hour, it defaults to the next full hour). | [optional] 
**splittable_usage** | [**EnergySchedulePostRequestSplittableUsage**](EnergySchedulePostRequestSplittableUsage.md) |  | [optional] 

## Example

```python
from evervolt.models.energy_schedule_post_request import EnergySchedulePostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of EnergySchedulePostRequest from a JSON string
energy_schedule_post_request_instance = EnergySchedulePostRequest.from_json(json)
# print the JSON string representation of the object
print(EnergySchedulePostRequest.to_json())

# convert the object into a dict
energy_schedule_post_request_dict = energy_schedule_post_request_instance.to_dict()
# create an instance of EnergySchedulePostRequest from a dict
energy_schedule_post_request_from_dict = EnergySchedulePostRequest.from_dict(energy_schedule_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


