# InlineObject1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**start** | **datetime** | Recommended optimal start time | [optional] 
**cost** | **float** | Cost if the device is started at the resulting time | [optional] 
**cost_now** | **float** | Cost if the device would be started now | [optional] 

## Example

```python
from evervolt.models.inline_object1 import InlineObject1

# TODO update the JSON string below
json = "{}"
# create an instance of InlineObject1 from a JSON string
inline_object1_instance = InlineObject1.from_json(json)
# print the JSON string representation of the object
print(InlineObject1.to_json())

# convert the object into a dict
inline_object1_dict = inline_object1_instance.to_dict()
# create an instance of InlineObject1 from a dict
inline_object1_from_dict = InlineObject1.from_dict(inline_object1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


