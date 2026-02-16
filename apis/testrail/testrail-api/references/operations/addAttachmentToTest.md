# POST /index.php?/api/v2/add_attachment_to_test/{test_id}

**Resource:** [attachments](../resources/attachments.md)
**Add attachment to test**
**Operation ID:** `addAttachmentToTest`

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
