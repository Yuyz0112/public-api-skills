# DELETE /attachments/{attachment_gid}

**Resource:** [Attachments](../resources/Attachments.md)
**Delete an attachment**
**Operation ID:** `deleteAttachment`

<b>Required scope: </b><code>attachments:delete</code>

Deletes a specific, existing attachment.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified attachment. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: attachments:delete
