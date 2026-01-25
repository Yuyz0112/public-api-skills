# PATCH /accounts/{account_id}/workers/workers/{worker_id}

**Resource:** [Workers](../resources/Workers.md)
**Edit Worker**
**Operation ID:** `editWorker`

Perform a partial update on a Worker, where omitted properties are left unchanged from their current values.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | workers_identifier | Yes |  |
| `worker_id` | path | string | Yes |  |

## Request Body

Worker partial update parameters.

**Required:** Yes

**Content Types:** `application/merge-patch+json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Partially Update Worker success. |
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
