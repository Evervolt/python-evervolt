# InlineObject1Inner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 
**name** | **str** |  | [optional] 
**usage_profile** | [**List[UsageProfileInner]**](UsageProfileInner.md) |  | [optional] 

## Example

```python
from evervolt.models.inline_object1_inner import InlineObject1Inner

# TODO update the JSON string below
json = "{}"
# create an instance of InlineObject1Inner from a JSON string
inline_object1_inner_instance = InlineObject1Inner.from_json(json)
# print the JSON string representation of the object
print(InlineObject1Inner.to_json())

# convert the object into a dict
inline_object1_inner_dict = inline_object1_inner_instance.to_dict()
# create an instance of InlineObject1Inner from a dict
inline_object1_inner_from_dict = InlineObject1Inner.from_dict(inline_object1_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


