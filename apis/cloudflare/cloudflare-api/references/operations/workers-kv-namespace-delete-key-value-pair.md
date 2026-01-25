# DELETE /accounts/{account_id}/storage/kv/namespaces/{namespace_id}/values/{key_name}

**Resource:** [Workers KV Namespace](../resources/Workers-KV-Namespace.md)
**Delete key-value pair**
**Operation ID:** `workers-kv-namespace-delete-key-value-pair`

Remove a KV pair from the namespace. Use URL-encoding to use special characters (for example, `:`, `!`, `%`) in the key name.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `key_name` | path | workers-kv_key_name | Yes |  |
| `namespace_id` | path | workers-kv_namespace_identifier | Yes |  |
| `account_id` | path | workers-kv_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete key-value pair response. |
| 4XX | Delete key-value pair response failure. |

**Success Response Schema:**

[workers-kv_api-response-common-no-result](../schemas/workers-kv/workers-kv-api-response-common-no-result.md)

## Security

- **api_token**
- **api_email**
- **api_key**
