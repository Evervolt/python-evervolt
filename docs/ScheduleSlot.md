# ScheduleSlot


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**start** | **datetime** | Start time of the slot | [optional] 
**end** | **datetime** | End time of the slot | [optional] 
**price** | **float** | Price per kWh | [optional] 

## Example

```python
from evervolt.models.schedule_slot import ScheduleSlot

# TODO update the JSON string below
json = "{}"
# create an instance of ScheduleSlot from a JSON string
schedule_slot_instance = ScheduleSlot.from_json(json)
# print the JSON string representation of the object
print(ScheduleSlot.to_json())

# convert the object into a dict
schedule_slot_dict = schedule_slot_instance.to_dict()
# create an instance of ScheduleSlot from a dict
schedule_slot_from_dict = ScheduleSlot.from_dict(schedule_slot_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


