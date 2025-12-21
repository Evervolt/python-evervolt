# DevicesDeleteRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** |  | [optional] 

## Example

```python
from evervolt.models.devices_delete_request import DevicesDeleteRequest

# TODO update the JSON string below
json = "{}"
# create an instance of DevicesDeleteRequest from a JSON string
devices_delete_request_instance = DevicesDeleteRequest.from_json(json)
# print the JSON string representation of the object
print(DevicesDeleteRequest.to_json())

# convert the object into a dict
devices_delete_request_dict = devices_delete_request_instance.to_dict()
# create an instance of DevicesDeleteRequest from a dict
devices_delete_request_from_dict = DevicesDeleteRequest.from_dict(devices_delete_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


