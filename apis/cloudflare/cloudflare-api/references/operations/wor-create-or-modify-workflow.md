# PUT /accounts/{account_id}/workflows/{workflow_name}

**Resource:** [Workflows](../resources/Workflows.md)
**Create/modify Workflow**
**Operation ID:** `wor-create-or-modify-workflow`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_name` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create/modify a Workflow based on a deployed script with an existing `WorkflowEntrypoint` class. Must be done after deploying the corresponding script. |
| 400 | Bad Request. |

## Security

- **api_email**
- **api_key**
- **api_token**
