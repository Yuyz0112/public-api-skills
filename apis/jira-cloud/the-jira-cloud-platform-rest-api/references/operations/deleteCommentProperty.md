# DELETE /rest/api/3/comment/{commentId}/properties/{propertyKey}

**Resource:** [Issue comment properties](../resources/Issue-comment-properties.md)
**Delete comment property**
**Operation ID:** `deleteCommentProperty`

Deletes a comment property.

**[Permissions](#permissions) required:** either of:

 *  *Edit All Comments* [project permission](https://confluence.atlassian.com/x/yodKLg) to delete a property from any comment.
 *  *Edit Own Comments* [project permission](https://confluence.atlassian.com/x/yodKLg) to delete a property from a comment created by the user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `commentId` | path | string | Yes | The ID of the comment. |
| `propertyKey` | path | string | Yes | The key of the property. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the comment or the property is not found. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
