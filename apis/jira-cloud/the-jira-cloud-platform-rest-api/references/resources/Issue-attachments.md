# Issue attachments

This resource represents issue attachments and the attachment settings for Jira. Use it to get the metadata for an attachment, delete an attachment, and view the metadata for the contents of an attachment. Also, use it to get the attachment settings for Jira.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/attachment/content/{id}` | Get attachment content | [View](../operations/getAttachmentContent.md) |
| GET | `/rest/api/3/attachment/meta` | Get Jira attachment settings | [View](../operations/getAttachmentMeta.md) |
| GET | `/rest/api/3/attachment/thumbnail/{id}` | Get attachment thumbnail | [View](../operations/getAttachmentThumbnail.md) |
| GET | `/rest/api/3/attachment/{id}` | Get attachment metadata | [View](../operations/getAttachment.md) |
| DELETE | `/rest/api/3/attachment/{id}` | Delete attachment | [View](../operations/removeAttachment.md) |
| GET | `/rest/api/3/attachment/{id}/expand/human` | Get all metadata for an expanded attachment | [View](../operations/expandAttachmentForHumans.md) |
| GET | `/rest/api/3/attachment/{id}/expand/raw` | Get contents metadata for an expanded attachment | [View](../operations/expandAttachmentForMachines.md) |
| POST | `/rest/api/3/issue/{issueIdOrKey}/attachments` | Add attachment | [View](../operations/addAttachment.md) |
