# DevicesPostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | [optional] 
**usage_profile** | [**List[UsageProfileInner]**](UsageProfileInner.md) |  | [optional] 

## Example

```python
from evervolt.models.devices_post_request import DevicesPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of DevicesPostRequest from a JSON string
devices_post_request_instance = DevicesPostRequest.from_json(json)
# print the JSON string representation of the object
print(DevicesPostRequest.to_json())

# convert the object into a dict
devices_post_request_dict = devices_post_request_instance.to_dict()
# create an instance of DevicesPostRequest from a dict
devices_post_request_from_dict = DevicesPostRequest.from_dict(devices_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


