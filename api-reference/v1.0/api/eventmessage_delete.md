# Delete eventMessage

Delete eventMessage.
### Prerequisites
One of the following **scopes** is required to execute this API: 
*Mail.ReadWrite* 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
DELETE /users/<id | userPrincipalName>/messages/<id>
DELETE /drive/root/createdByUser/messages/<id>
DELETE /drive/root/lastModifiedByUser/messages/<id>

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| Authorization  | string  | Bearer <token>. Required. |

### Request body
Do not supply a request body for this method.


### Response
If successful, this method returns `204, No Content` response code. It does not return anything in the response body.

### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "delete_eventmessage"
}-->
```http
DELETE https://graph.microsoft.com/v1.0/me/messages/<id>
```
##### Response
Here is an example of the response. 
<!-- {
  "blockType": "response",
  "truncated": true
} -->
```http
HTTP/1.1 204 No Content
```
<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Delete eventMessage",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->