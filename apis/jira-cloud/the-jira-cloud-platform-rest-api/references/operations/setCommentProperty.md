# PUT /rest/api/3/comment/{commentId}/properties/{propertyKey}

**Resource:** [Issue comment properties](../resources/Issue-comment-properties.md)
**Set comment property**
**Operation ID:** `setCommentProperty`

Creates or updates the value of a property for a comment. Use this resource to store custom data against a comment.

The value of the request body must be a [valid](http://tools.ietf.org/html/rfc4627), non-empty JSON blob. The maximum length is 32768 characters.

**[Permissions](#permissions) required:** either of:

 *  *Edit All Comments* [project permission](https://confluence.atlassian.com/x/yodKLg) to create or update the value of a property on any comment.
 *  *Edit Own Comments* [project permission](https://confluence.atlassian.com/x/yodKLg) to create or update the value of a property on a comment created by the user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `commentId` | path | string | Yes | The ID of the comment. |
| `propertyKey` | path | string | Yes | The key of the property. The maximum length is 255 characters. |

## Request Body

The value of the property. The value has to be a valid, non-empty [JSON](https://tools.ietf.org/html/rfc4627) value. The maximum length of the property value is 32768 bytes.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the comment property is updated. |
| 201 | Returned if the comment property is created. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the comment is not found. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
