# PUT /accounts/{account_id}/workers/workers/{worker_id}

**Resource:** [Workers](../resources/Workers.md)
**Update Worker**
**Operation ID:** `updateWorker`

Perform a complete replacement of a Worker, where omitted properties are set to their default values. This is the exact same as the Create Worker endpoint, but operates on an existing Worker. To perform a partial update instead, use the Edit Worker endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `worker_id` | path | string | Yes |  |

## Request Body

Worker update parameters.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Worker success. |
| 400 | Bad Request - Invalid input data. |
| 401 | (reference) |
| 403 | Forbidden - Insufficient permissions or quota exceeded. |
| 404 | (reference) |
| 409 | Conflict - Worker name already exists. |
| 500 | (reference) |

## Security

- **api_token**
- **api_email**
- **api_key**
