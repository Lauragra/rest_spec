# List PimAlertSettings

Retrieve a list of pimalertsettings objects.
### HTTP request
```http
GET /AlertSettings
```
### Optional query parameters
You can use the [OData query parameters](odata-optional-query-parameters.md) to restrict the shape of the objects returned from this call.
### Request headers
| Name       | Type | Description|
|:-----------|:------|:----------|
| X-Sample-Header  | string  | Sample of how the HTTP headers used by the API could be displayed.|

### Request body
Do not supply a request body for this method.
### Response
If successful, this method returns a `200 OK` response code and collection of [PimAlertSettings](../resources/pimalertsettings.md) objects in the response body.
### Example
##### Response
Here is an example of the response.
```json
HTTP/1.1 200 OK
Content-type: application/json
Content-length: 74
{
  "AlertId": "AlertId-value",
  "AlertSettings": "AlertSettings-value"
}
```

<!-- uuid: 79ebe35e-cc93-49e0-bc15-911549fad29c
2015-10-09 18:31:36 UTC -->