# DELETE /accounts/{account_id}/storage/kv/namespaces/{namespace_id}/bulk

**Resource:** [Workers KV Namespace](../resources/Workers-KV-Namespace.md)
**Delete multiple key-value pairs**
**Operation ID:** `workers-kv-namespace-delete-multiple-key-value-pairs-deprecated`
⚠️ **Deprecated**

Remove multiple KV pairs from the namespace. Body should be an array of up to 10,000 keys to be removed.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace_id` | path | workers-kv_namespace_identifier | Yes |  |
| `account_id` | path | workers-kv_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers-kv_bulk_delete](../schemas/workers-kv/workers-kv-bulk-delete.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Delete multiple key-value pairs response. |
| 4XX | Delete multiple key-value pairs response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
