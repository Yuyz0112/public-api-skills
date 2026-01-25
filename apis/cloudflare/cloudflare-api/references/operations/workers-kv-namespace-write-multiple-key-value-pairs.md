# PUT /accounts/{account_id}/storage/kv/namespaces/{namespace_id}/bulk

**Resource:** [Workers KV Namespace](../resources/Workers-KV-Namespace.md)
**Write multiple key-value pairs**
**Operation ID:** `workers-kv-namespace-write-multiple-key-value-pairs`

Write multiple keys and values at once. Body should be an array of up to 10,000 key-value pairs to be stored, along with optional expiration information. Existing values and expirations will be overwritten. If neither `expiration` nor `expiration_ttl` is specified, the key-value pair will never expire. If both are set, `expiration_ttl` is used and `expiration` is ignored. The entire request size must be 100 megabytes or less.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace_id` | path | workers-kv_namespace_identifier | Yes |  |
| `account_id` | path | workers-kv_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers-kv_bulk_write](../schemas/workers-kv/workers-kv-bulk-write.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Write multiple key-value pairs response. |
| 4XX | Write multiple key-value pairs response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
