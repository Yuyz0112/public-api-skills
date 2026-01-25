# IssueTypeIssueCreateMetadata

Details of the issue creation metadata for an issue type.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `avatarId` | integer (int64) | No | The ID of the issue type's avatar. |
| `description` | string | No | The description of the issue type. |
| `entityId` | string (uuid) | No | Unique ID for next-gen projects. |
| `expand` | string | No | Expand options that include additional issue type metadata details in the response. |
| `fields` | object | No | List of the fields available when creating an issue for the issue type. |
| `hierarchyLevel` | integer (int32) | No | Hierarchy level of the issue type. |
| `iconUrl` | string | No | The URL of the issue type's avatar. |
| `id` | string | No | The ID of the issue type. |
| `name` | string | No | The name of the issue type. |
| `scope` | any | No | Details of the next-gen projects the issue type is available in. |
| `self` | string | No | The URL of these issue type details. |
| `subtask` | boolean | No | Whether this issue type is used to create subtasks. |

