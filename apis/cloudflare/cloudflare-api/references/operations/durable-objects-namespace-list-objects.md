# GET /accounts/{account_id}/workers/durable_objects/namespaces/{id}/objects

**Resource:** [Durable Objects Namespace](../resources/Durable-Objects-Namespace.md)
**List Objects**
**Operation ID:** `durable-objects-namespace-list-objects`

Returns the Durable Objects in a given namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `id` | path | workers_schemas-id | Yes |  |
| `limit` | query | number | No |  |
| `cursor` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Objects response. |
| 4XX | List Objects response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
