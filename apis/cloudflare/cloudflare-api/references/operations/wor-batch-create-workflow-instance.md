# POST /accounts/{account_id}/workflows/{workflow_name}/instances/batch

**Resource:** [Workflows](../resources/Workflows.md)
**Batch create new Workflow instances**
**Operation ID:** `wor-batch-create-workflow-instance`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_name` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Batch create workflow instances. Body is a JSON list that contain all payloads and ids that are passed into the new instance as the event payload. |
| 400 | Provided Workflow ID is not valid. |
| 404 | Workflow Name not found. |

## Security

- **api_email**
- **api_key**
- **api_token**
