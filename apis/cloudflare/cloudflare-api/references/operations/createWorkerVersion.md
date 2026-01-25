# POST /accounts/{account_id}/workers/workers/{worker_id}/versions

**Resource:** [Versions](../resources/Versions.md)
**Create Version**
**Operation ID:** `createWorkerVersion`

Create a new version.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `worker_id` | path | string | Yes |  |
| `deploy` | query | boolean | No |  |

## Request Body

Version creation parameters.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [workers_Version](../schemas/workers/workers-Version.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create version success. |
| 4XX | Create version failure. |

## Security

- **api_token**
- **api_email**
- **api_key**
