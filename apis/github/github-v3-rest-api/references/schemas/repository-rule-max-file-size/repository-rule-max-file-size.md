# repository-rule-max-file-size

Prevent commits with individual files that exceed the specified limit from being pushed to the commit graph.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: max_file_size | Yes |  |
| `parameters` | object | No |  |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `max_file_size` | integer | Yes | The maximum file size allowed in megabytes. This limit does not apply to Git Large File Storage (Git LFS). |

