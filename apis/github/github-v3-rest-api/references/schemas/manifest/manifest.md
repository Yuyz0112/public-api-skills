# manifest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `name` | string | Yes | The name of the manifest. |
| `file` | object | No |  |
| `metadata` | [metadata](metadata.md) | No |  |
| `resolved` | object | No | A collection of resolved package dependencies. |

## Nested Fields

### `file`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `source_location` | string | No | The path of the manifest file relative to the root of the Git repository. |

