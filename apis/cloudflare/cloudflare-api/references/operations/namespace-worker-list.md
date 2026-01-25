# GET /accounts/{account_id}/workers/dispatch/namespaces

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**List dispatch namespaces**
**Operation ID:** `namespace-worker-list`

Fetch a list of Workers for Platforms namespaces.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch a list of Workers for Platforms namespaces. |
| 4XX | Failure to get list of Workers for Platforms namespaces. |

**Success Response Schema:**

[workers_namespace-list-response](../schemas/workers/workers-namespace-list-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
