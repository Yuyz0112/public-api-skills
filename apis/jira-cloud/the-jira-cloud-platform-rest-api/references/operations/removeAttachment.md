# DELETE /rest/api/3/attachment/{id}

**Resource:** [Issue attachments](../resources/Issue-attachments.md)
**Delete attachment**
**Operation ID:** `removeAttachment`

Deletes an attachment from an issue.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** For the project holding the issue containing the attachment:

 *  *Delete own attachments* [project permission](https://confluence.atlassian.com/x/yodKLg) to delete an attachment created by the calling user.
 *  *Delete all attachments* [project permission](https://confluence.atlassian.com/x/yodKLg) to delete an attachment created by any user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the attachment. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if:

 *  the attachment is not found.
 *  attachments are disabled in the Jira settings. |

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
