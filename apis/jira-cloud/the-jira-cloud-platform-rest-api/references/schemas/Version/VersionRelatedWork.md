# VersionRelatedWork

Associated related work to a version

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `category` | string | Yes | The category of the related work |
| `issueId` | integer (int64) | No | The ID of the issue associated with the related work (if there is one). Cannot be updated via the Rest API. |
| `relatedWorkId` | string | No | The id of the related work. For the native release note related work item, this will be null, and Rest API does not support updating it. |
| `title` | string | No | The title of the related work |
| `url` | string (uri) | No | The URL of the related work. Will be null for the native release note related work item, but is otherwise required. |

