# List Application

Retrieve a list of application objects.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
GET /applications
```
### Optional query parameters
|Name|Value|Description|
|:---------------|:--------|:-------|
|$orderby|string|Comma-separated list of properties that are used to sort the order of items in the response collection.|

### Request headers
| Name       | Type | Description|
|:-----------|:------|:----------|
| X-Sample-Header  | string  | Sample of how the HTTP header. Update accordingly...|

### Request body
Do not supply a request body for this method.
### Response
If successful, this method returns a `200 OK` response code and collection of [Application](../resources/application.md) objects in the response body.
### Example
##### Response
Here is an example of the response.
<!-- {
  "blockType": "response",
  "truncated": false,
  "@odata.type": "applications"
} -->
```json
HTTP/1.1 200 OK
Content-type: application/json
Content-length: 2442
{
  "values": [
    {
      "appId": "appId-value",
      "appRoles": [
        {
          "allowedMemberTypes": "allowedMemberTypes-value",
          "description": "description-value",
          "displayName": "displayName-value",
          "id": "id-value",
          "isEnabled": true,
          "value": "value-value"
        }
      ],
      "availableToOtherTenants": true,
      "displayName": "displayName-value",
      "errorUrl": "errorUrl-value",
      "groupMembershipClaims": "groupMembershipClaims-value",
      "homepage": "homepage-value",
      "identifierUris": [
        "identifierUris-value"
      ],
      "keyCredentials": [
        {
          "customKeyIdentifier": "customKeyIdentifier-value",
          "endDate": "datetime-value",
          "keyId": "keyId-value",
          "startDate": "datetime-value",
          "type": "type-value",
          "usage": "usage-value",
          "value": "value-value"
        }
      ],
      "knownClientApplications": [
        "knownClientApplications-value"
      ],
      "mainLogo": "mainLogo-value",
      "logoutUrl": "logoutUrl-value",
      "oauth2AllowImplicitFlow": true,
      "oauth2AllowUrlPathMatching": true,
      "oauth2Permissions": [
        {
          "adminConsentDescription": "adminConsentDescription-value",
          "adminConsentDisplayName": "adminConsentDisplayName-value",
          "id": "id-value",
          "isEnabled": true,
          "type": "type-value",
          "userConsentDescription": "userConsentDescription-value",
          "userConsentDisplayName": "userConsentDisplayName-value",
          "value": "value-value"
        }
      ],
      "oauth2RequirePostResponse": true,
      "passwordCredentials": [
        {
          "customKeyIdentifier": "customKeyIdentifier-value",
          "endDate": "datetime-value",
          "keyId": "keyId-value",
          "startDate": "datetime-value",
          "value": "value-value"
        }
      ],
      "publicClient": true,
      "replyUrls": [
        "replyUrls-value"
      ],
      "requiredResourceAccess": [
        {
          "resourceAppId": "resourceAppId-value",
          "resourceAccess": {
            "id": "id-value",
            "type": "type-value"
          }
        }
      ],
      "samlMetadataUrl": "samlMetadataUrl-value",
      "objectType": "objectType-value",
      "objectId": "objectId-value",
      "deletionTimestamp": "datetime-value"
    }
  ]
}
```
If successful, this method returns a `200 OK` response code and collection of [Application](../resources/application.md) objects in the response body.

<!-- uuid: 19f7a9d9-3f67-4c30-b3d9-73d3dc6f01a4
2015-10-16 09:34:38 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "List Application",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->