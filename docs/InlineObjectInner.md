# InlineObjectInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**usage_profile** | [**List[UsageProfileInner]**](UsageProfileInner.md) |  | [optional] 

## Example

```python
from evervolt.models.inline_object_inner import InlineObjectInner

# TODO update the JSON string below
json = "{}"
# create an instance of InlineObjectInner from a JSON string
inline_object_inner_instance = InlineObjectInner.from_json(json)
# print the JSON string representation of the object
print(InlineObjectInner.to_json())

# convert the object into a dict
inline_object_inner_dict = inline_object_inner_instance.to_dict()
# create an instance of InlineObjectInner from a dict
inline_object_inner_from_dict = InlineObjectInner.from_dict(inline_object_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


