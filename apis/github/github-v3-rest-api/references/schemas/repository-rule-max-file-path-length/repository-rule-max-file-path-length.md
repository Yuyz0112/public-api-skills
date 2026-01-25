# repository-rule-max-file-path-length

Prevent commits that include file paths that exceed the specified character limit from being pushed to the commit graph.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: max_file_path_length | Yes |  |
| `parameters` | object | No |  |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `max_file_path_length` | integer | Yes | The maximum amount of characters allowed in file paths. |

