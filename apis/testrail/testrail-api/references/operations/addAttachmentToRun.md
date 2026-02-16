# POST /index.php?/api/v2/add_attachment_to_run/{run_id}

**Resource:** [attachments](../resources/attachments.md)
**Add attachment to run**
**Operation ID:** `addAttachmentToRun`

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

**Schema:** [AddAttachmentRequest](../schemas/Add/AddAttachmentRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Created attachment |
| default | (reference) |

**Success Response Schema:**

[Attachment](../schemas/Attachment/Attachment.md)

## Security

- **basicAuth**
