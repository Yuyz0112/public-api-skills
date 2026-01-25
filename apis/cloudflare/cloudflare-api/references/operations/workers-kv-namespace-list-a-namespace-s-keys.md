# GET /accounts/{account_id}/storage/kv/namespaces/{namespace_id}/keys

**Resource:** [Workers KV Namespace](../resources/Workers-KV-Namespace.md)
**List a Namespace's Keys**
**Operation ID:** `workers-kv-namespace-list-a-namespace'-s-keys`

Lists a namespace's keys.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace_id` | path | workers-kv_namespace_identifier | Yes |  |
| `account_id` | path | workers-kv_identifier | Yes |  |
| `limit` | query | number | No |  |
| `prefix` | query | string | No |  |
| `cursor` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List a Namespace's Keys response. |
| 4XX | List a Namespace's Keys response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
