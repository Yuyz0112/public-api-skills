# teams-devices_file_input_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `exists` | boolean | No | Whether or not file exists. |
| `operating_system` | enum: windows, linux, mac | Yes | Operating system. |
| `path` | string | Yes | File path. |
| `sha256` | string | No | SHA-256. |
| `thumbprint` | string | No | Signing certificate thumbprint. |

