# workers-kv_key

A name for a value. A value stored under a given key may be retrieved via the same key.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `expiration` | number | No | The time, measured in number of seconds since the UNIX epoch, at which the key will expire. This property is omitted for keys that will not expire. |
| `metadata` | [workers-kv_list_metadata](workers-kv-list-metadata.md) | No |  |
| `name` | [workers-kv_key_name](workers-kv-key-name.md) | Yes |  |

