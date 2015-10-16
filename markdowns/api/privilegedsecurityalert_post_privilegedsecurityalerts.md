# Create PrivilegedSecurityAlert

Use this API to create a new PrivilegedSecurityAlert.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
POST /PrivilegedSecurityAlerts

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| X-Sample-Header  | string  | Sample HTTP header. Update accordingly or remove if not needed|

### Request body
In the request body, supply a JSON representation of [PrivilegedSecurityAlert](../resources/privilegedsecurityalert.md) object.


### Response
If successful, this method returns `201, Created` response code and [PrivilegedSecurityAlert](../resources/privilegedsecurityalert.md) object in the response body.

### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "create_privilegedsecurityalert_from_privilegedsecurityalerts"
}-->
```http
POST /PrivilegedSecurityAlerts
Content-type: application/json
```
In the request body, supply a JSON representation of [PrivilegedSecurityAlert](../resources/privilegedsecurityalert.md) object.
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "privilegedsecurityalert"
} -->
```json
HTTP/1.1 201 Created
Content-type: application/json
Content-length: 596
{
  "AlertId": "AlertId-value",
  "NumberOfAffectedItems": 99,
  "AdditionalData": "AdditionalData-value",
  "AlertName": "AlertName-value",
  "AlertDescription": "AlertDescription-value",
  "LastModifiedTime": "datetime-value",
  "LastScannedTime": "datetime-value",
  "SeverityLevel": "SeverityLevel-value",
  "AlertType": "AlertType-value",
  "SecurityImpact": "SecurityImpact-value",
  "MitigationSteps": "MitigationSteps-value",
  "HowToPrevent": "HowToPrevent-value",
  "WasDismissed": true,
  "IsActive": true,
  "IsResolvable": true,
  "IsConfigurable": true,
  "Status": "Status-value"
}
```

<!-- uuid: c3001d58-4c80-450f-85bf-53369dd4324a
2015-10-16 21:11:01 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Create PrivilegedSecurityAlert",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->