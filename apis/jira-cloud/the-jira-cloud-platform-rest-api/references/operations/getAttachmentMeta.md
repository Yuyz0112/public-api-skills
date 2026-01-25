# GET /rest/api/3/attachment/meta

**Resource:** [Issue attachments](../resources/Issue-attachments.md)
**Get Jira attachment settings**
**Operation ID:** `getAttachmentMeta`

Returns the attachment settings, that is, whether attachments are enabled and the maximum attachment size allowed.

Note that there are also [project permissions](https://confluence.atlassian.com/x/yodKLg) that restrict whether users can create and delete attachments.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[AttachmentSettings](../schemas/Attachment/AttachmentSettings.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
