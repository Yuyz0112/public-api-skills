# GET /rest/api/3/attachment/{id}

**Resource:** [Issue attachments](../resources/Issue-attachments.md)
**Get attachment metadata**
**Operation ID:** `getAttachment`

Returns the metadata for an attachment. Note that the attachment itself is not returned.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:**

 *  *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project that the issue is in.
 *  If [issue-level security](https://confluence.atlassian.com/x/J4lKLg) is configured, issue-level security permission to view the issue.
 *  If attachments are added in private comments, the comment-level restriction will be applied.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the attachment. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if:

 *  the attachment is not found.
 *  attachments are disabled in the Jira settings. |

**Success Response Schema:**

[AttachmentMetadata](../schemas/Attachment/AttachmentMetadata.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
