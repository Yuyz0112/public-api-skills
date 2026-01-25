# POST /accounts/{account_id}/workflows/{workflow_name}/instances/{instance_id}/events/{event_type}

**Resource:** [Workflows](../resources/Workflows.md)
**Send event to instance**
**Operation ID:** `wor-send-event-workflow-instance`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_name` | path | string | Yes |  |
| `instance_id` | path | string | Yes |  |
| `event_type` | path | string | Yes |  |
| `account_id` | path | string | Yes |  |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Send an event to an instance. |
| 400 | Bad Request. |
| 404 | Workflow not found. |

## Security

- **api_email**
- **api_key**
- **api_token**
