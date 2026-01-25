# AttachmentArchiveMetadataReadable

Metadata for an archive (for example a zip) and its contents.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `entries` | AttachmentArchiveItemReadable[] | No | The list of the items included in the archive. |
| `id` | integer (int64) | No | The ID of the attachment. |
| `mediaType` | string | No | The MIME type of the attachment. |
| `name` | string | No | The name of the archive file. |
| `totalEntryCount` | integer (int64) | No | The number of items included in the archive. |

