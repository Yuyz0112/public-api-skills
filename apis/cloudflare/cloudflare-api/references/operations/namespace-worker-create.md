# POST /accounts/{account_id}/workers/dispatch/namespaces

**Resource:** [Workers for Platforms](../resources/Workers-for-Platforms.md)
**Create dispatch namespace**
**Operation ID:** `namespace-worker-create`

Create a new Workers for Platforms namespace.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Fetch a list of Workers for Platforms namespaces. |
| 4XX | Failure to get list of Workers for Platforms namespaces. |

**Success Response Schema:**

[workers_namespace-single-response](../schemas/workers/workers-namespace-single-response.md)

## Security

- **api_token**
- **api_email**
- **api_key**
