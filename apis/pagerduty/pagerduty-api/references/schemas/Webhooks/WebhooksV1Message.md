# WebhooksV1Message

A message containing information about a single PagerDuty action.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string (uuid) | No | Uniquely identifies this outgoing webhook message; can be used for idempotency when processing the messages. |
| `type` | enum: incident.trigger, incident.acknowledge, incident.unacknowledge... | No | The type of action being reported by this message. |
| `created_on` | string (date-time) | No | The date/time when the incident changed state. |
| `data` | object | No |  |

## Nested Fields

### `data`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `incident` | [WebhooksV1IncidentData](WebhooksV1IncidentData.md) | No |  |

