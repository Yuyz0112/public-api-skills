# GET /accounts/{account_id}/storage/kv/namespaces/{namespace_id}/metadata/{key_name}

**Resource:** [Workers KV Namespace](../resources/Workers-KV-Namespace.md)
**Read the metadata for a key**
**Operation ID:** `workers-kv-namespace-read-the-metadata-for-a-key`

Returns the metadata associated with the given key in the given namespace. Use URL-encoding to use special characters (for example, `:`, `!`, `%`) in the key name.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key_name` | path | workers-kv_key_name | Yes |  |
| `namespace_id` | path | workers-kv_namespace_identifier | Yes |  |
| `account_id` | path | workers-kv_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Read the metadata for a key response. |
| 4XX | Read the metadata for a key response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
