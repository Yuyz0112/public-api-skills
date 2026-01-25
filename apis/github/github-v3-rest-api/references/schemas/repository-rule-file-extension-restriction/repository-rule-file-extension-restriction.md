# repository-rule-file-extension-restriction

Prevent commits that include files with specified file extensions from being pushed to the commit graph.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: file_extension_restriction | Yes |  |
| `parameters` | object | No |  |

## Nested Fields

### `parameters`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `restricted_file_extensions` | string[] | Yes | The file extensions that are restricted from being pushed to the commit graph. |

