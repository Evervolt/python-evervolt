# EnergySchedulePostRequestSplittableUsage


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**duration** | **str** |  | [optional] 
**usage** | **float** | Usage in kW for the given duration | [optional] 

## Example

```python
from evervolt.models.energy_schedule_post_request_splittable_usage import EnergySchedulePostRequestSplittableUsage

# TODO update the JSON string below
json = "{}"
# create an instance of EnergySchedulePostRequestSplittableUsage from a JSON string
energy_schedule_post_request_splittable_usage_instance = EnergySchedulePostRequestSplittableUsage.from_json(json)
# print the JSON string representation of the object
print(EnergySchedulePostRequestSplittableUsage.to_json())

# convert the object into a dict
energy_schedule_post_request_splittable_usage_dict = energy_schedule_post_request_splittable_usage_instance.to_dict()
# create an instance of EnergySchedulePostRequestSplittableUsage from a dict
energy_schedule_post_request_splittable_usage_from_dict = EnergySchedulePostRequestSplittableUsage.from_dict(energy_schedule_post_request_splittable_usage_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


