# POST /accounts/{account_id}/storage/kv/namespaces/{namespace_id}/bulk/get

**Resource:** [Workers KV Namespace](../resources/Workers-KV-Namespace.md)
**Get multiple key-value pairs**
**Operation ID:** `workers-kv-namespace-get-multiple-key-value-pairs`

Retrieve up to 100 KV pairs from the namespace. Keys must contain text-based values. JSON values can optionally be parsed instead of being returned as a string value. Metadata can be included if `withMetadata` is true.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace_id` | path | workers-kv_namespace_identifier | Yes |  |
| `account_id` | path | workers-kv_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get multiple key-value pairs response. |
| 4XX | Get multiple key-value pairs response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
