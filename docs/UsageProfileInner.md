# UsageProfileInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**duration** | **str** |  | [optional] 
**usage** | **float** | Usage in kWh for the given duration | [optional] 

## Example

```python
from evervolt.models.usage_profile_inner import UsageProfileInner

# TODO update the JSON string below
json = "{}"
# create an instance of UsageProfileInner from a JSON string
usage_profile_inner_instance = UsageProfileInner.from_json(json)
# print the JSON string representation of the object
print(UsageProfileInner.to_json())

# convert the object into a dict
usage_profile_inner_dict = usage_profile_inner_instance.to_dict()
# create an instance of UsageProfileInner from a dict
usage_profile_inner_from_dict = UsageProfileInner.from_dict(usage_profile_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


