# DELETE /accounts/{account_id}/workflows/{workflow_name}

**Resource:** [Workflows](../resources/Workflows.md)
**Deletes a Workflow**
**Operation ID:** `wor-delete-workflow`

Deletes a Workflow. This only deletes the Workflow and does not delete or modify any Worker associated to this Workflow or bounded to it.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_name` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Deletes a Workflow. |
| 400 | Workflow has no deployed versions. |
| 404 | Workflow not found. |

## Security

- **api_email**
- **api_key**
- **api_token**
