# POST /index.php?/api/v2/add_attachment_to_plan_entry/{plan_entry_id}

**Resource:** [attachments](../resources/attachments.md)
**Add attachment to plan entry**
**Operation ID:** `addAttachmentToPlanEntry`

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
