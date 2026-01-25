# WebhooksV1IncidentData

The incident details at the time of the state change.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `incident_number` | integer | No | The number of the incident. This is unique across the account. |
| `created_on` | string (date-time) | No | The date/time the incident was first triggered. |
| `status` | enum: triggered, acknowledged, resolved | No | The current status of the incident. |
| `html_url` | string (url) | No |  |
| `incident_key` | string | No | The incident's de-duplication key. |
| `service` | [WebhooksV1Service](WebhooksV1Service.md) | No |  |
| `assigned_to_user` | [WebhooksV1AssignedToUser](WebhooksV1AssignedToUser.md) | No |  |
| `assigned_to` | WebhooksV1AssignedTo[] | No |  |
| `trigger_summary_data` | object | No |  |
| `trigger_details_html_url` | string (url) | No |  |
| `last_status_change_on` | string (date-time) | No | The time at which the status of the incident last changed. |
| `last_status_change_by` | [WebhooksV1AssignedToUser](WebhooksV1AssignedToUser.md) | No |  |
| `number_of_escalations` | integer | No | Number of times the incident has been escalated. |
| `urgency` | enum: high, low | No |  |

## Nested Fields

### `trigger_summary_data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `subject` | string | No |  |

