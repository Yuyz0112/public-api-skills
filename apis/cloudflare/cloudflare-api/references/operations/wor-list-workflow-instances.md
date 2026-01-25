# GET /accounts/{account_id}/workflows/{workflow_name}/instances

**Resource:** [Workflows](../resources/Workflows.md)
**List of workflow instances**
**Operation ID:** `wor-list-workflow-instances`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `workflow_name` | path | string | Yes |  |
| `page` | query | number | No | `page` and `cursor` are mutually exclusive, use one or the other. |
| `per_page` | query | number | No |  |
| `cursor` | query | string | No | `page` and `cursor` are mutually exclusive, use one or the other. |
| `direction` | query | enum: asc, desc | No | should only be used when `cursor` is used, defines a new direction for the cursor |
| `status` | query | enum: queued, running, paused... | No |  |
| `date_start` | query | string (date-time) | No | Accepts ISO 8601 with no timezone offsets and in UTC. |
| `date_end` | query | string (date-time) | No | Accepts ISO 8601 with no timezone offsets and in UTC. |
| `account_id` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List of workflow instances. |
| 400 | Input Validation Error. |
| 404 | Workflow Name not found. |

## Security

- **api_email**
- **api_key**
- **api_token**
