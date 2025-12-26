# InlineObject2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**start** | **datetime** | Recommended optimal start time | [optional] 
**cost** | **float** | Cost if the device is started at the resulting time | [optional] 
**cost_now** | **float** | Cost if the device would be started now | [optional] 

## Example

```python
from evervolt.models.inline_object2 import InlineObject2

# TODO update the JSON string below
json = "{}"
# create an instance of InlineObject2 from a JSON string
inline_object2_instance = InlineObject2.from_json(json)
# print the JSON string representation of the object
print(InlineObject2.to_json())

# convert the object into a dict
inline_object2_dict = inline_object2_instance.to_dict()
# create an instance of InlineObject2 from a dict
inline_object2_from_dict = InlineObject2.from_dict(inline_object2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


