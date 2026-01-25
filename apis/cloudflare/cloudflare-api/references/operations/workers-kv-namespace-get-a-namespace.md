# GET /accounts/{account_id}/storage/kv/namespaces/{namespace_id}

**Resource:** [Workers KV Namespace](../resources/Workers-KV-Namespace.md)
**Get a Namespace**
**Operation ID:** `workers-kv-namespace-get-a-namespace`

Get the namespace corresponding to the given ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `namespace_id` | path | workers-kv_namespace_identifier | Yes |  |
| `account_id` | path | workers-kv_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get a Namespace response. |
| 4XX | Get a Namespace response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
