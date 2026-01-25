# POST /accounts/{account_id}/workflows/{workflow_name}/instances/batch/terminate

**Resource:** [Workflows](../resources/Workflows.md)
**Batch terminate instances of a workflow**
**Operation ID:** `wor-batch-terminate-workflow-instances`

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
| 200 | Batch terminate instances of a workflow, via a async job. Body is a JSON list that contain the ids of the instances to terminate. |
| 400 | Provided Workflow ID is not valid. |
| 404 | Workflow Name not found. |

## Security

- **api_email**
- **api_key**
- **api_token**
