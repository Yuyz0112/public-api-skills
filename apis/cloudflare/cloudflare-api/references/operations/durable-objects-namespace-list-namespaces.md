# GET /accounts/{account_id}/workers/durable_objects/namespaces

**Resource:** [Durable Objects Namespace](../resources/Durable-Objects-Namespace.md)
**List Namespaces**
**Operation ID:** `durable-objects-namespace-list-namespaces`

Returns the Durable Object namespaces owned by an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `page` | query | integer | No | Current page. |
| `per_page` | query | integer | No | Items per-page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Namespaces response. |
| 4XX | List Namespaces response failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
