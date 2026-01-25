# cvss-severities

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `cvss_v3` | object | No |  |
| `cvss_v4` | object | No |  |

## Nested Fields

### `cvss_v3`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `vector_string` | string | Yes | The CVSS 3 vector string. |
| `score` | number | Yes | The CVSS 3 score. |

### `cvss_v4`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `vector_string` | string | Yes | The CVSS 4 vector string. |
| `score` | number | Yes | The CVSS 4 score. |

