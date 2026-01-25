# r2_temp_access_creds_request

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `bucket` | string | Yes | Name of the R2 bucket. |
| `objects` | string[] | No | Optional object paths to scope the credentials to. |
| `parentAccessKeyId` | string | Yes | The parent access key id to use for signing. |
| `permission` | enum: admin-read-write, admin-read-only, object-read-write... | Yes | Permissions allowed on the credentials. |
| `prefixes` | string[] | No | Optional prefix paths to scope the credentials to. |
| `ttlSeconds` | number | Yes | How long the credentials will live for in seconds. |

