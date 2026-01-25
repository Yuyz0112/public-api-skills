# POST /accounts/{account_id}/workflows/{workflow_name}/instances

**Resource:** [Workflows](../resources/Workflows.md)
**Create a new workflow instance**
**Operation ID:** `wor-create-new-workflow-instance`

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
| 200 | Create workflow instance. Body is a JSON parsable string that it's passed into the new instance as the event payload. |
| 400 | Provided Workflow ID is not valid. |
| 404 | Workflow Name not found. |

## Security

- **api_email**
- **api_key**
- **api_token**
