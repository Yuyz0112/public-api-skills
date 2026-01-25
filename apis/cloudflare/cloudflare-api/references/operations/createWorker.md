# POST /accounts/{account_id}/workers/workers

**Resource:** [Workers](../resources/Workers.md)
**Create Worker**
**Operation ID:** `createWorker`

Create a new Worker.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |

## Request Body

Worker creation parameters.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Worker success. |
| 400 | Bad Request - Invalid input data. |
| 401 | (reference) |
| 403 | Forbidden - Access denied or limit exceeded. |
| 409 | Conflict - Resource already exists. |
| 500 | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
