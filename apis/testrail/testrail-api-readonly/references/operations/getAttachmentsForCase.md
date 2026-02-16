# GET /index.php?/api/v2/get_attachments_for_case/{case_id}

**Resource:** [read](../resources/read.md)
**Get attachments for case**
**Operation ID:** `getAttachmentsForCase`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Attachment list |
| default | (reference) |

**Success Response Schema:**

Array of [Attachment](../schemas/Attachment/Attachment.md)

## Security

- **basicAuth**
