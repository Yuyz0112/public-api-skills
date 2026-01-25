# workers-kv_bulk-result

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `successful_key_count` | number | No | Number of keys successfully updated. |
| `unsuccessful_keys` | string[] | No | Name of the keys that failed to be fully updated. They should be retried. |

