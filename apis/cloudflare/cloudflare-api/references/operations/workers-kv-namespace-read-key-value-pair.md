# GET /accounts/{account_id}/storage/kv/namespaces/{namespace_id}/values/{key_name}

**Resource:** [Workers KV Namespace](../resources/Workers-KV-Namespace.md)
**Read key-value pair**
**Operation ID:** `workers-kv-namespace-read-key-value-pair`

Returns the value associated with the given key in the given namespace. Use URL-encoding to use special characters (for example, `:`, `!`, `%`) in the key name. If the KV-pair is set to expire at some point, the expiration time as measured in seconds since the UNIX epoch will be returned in the `expiration` response header.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key_name` | path | workers-kv_key_name | Yes |  |
| `namespace_id` | path | workers-kv_namespace_identifier | Yes |  |
| `account_id` | path | workers-kv_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Read key-value pair response. |
| 4XX | Read key-value pair response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
