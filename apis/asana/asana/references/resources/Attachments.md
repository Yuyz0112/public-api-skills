# Attachments

An *attachment* object represents any file attached to a task in Asana, whether it's an uploaded file or one associated via a third-party service such as Dropbox or Google Drive.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/attachments/{attachment_gid}` | Get an attachment | [View](../operations/getAttachment.md) |
| DELETE | `/attachments/{attachment_gid}` | Delete an attachment | [View](../operations/deleteAttachment.md) |
| GET | `/attachments` | Get attachments from an object | [View](../operations/getAttachmentsForObject.md) |
| POST | `/attachments` | Upload an attachment | [View](../operations/createAttachmentForObject.md) |
