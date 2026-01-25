# ResponderRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `incident` | [IncidentReference](IncidentReference.md) | No |  |
| `requester` | [UserReference](UserReference.md) | No |  |
| `requested_at` | string | No | The time the request was made |
| `message` | string | No | The message sent with the responder request |
| `responder_request_targets` | ResponderRequestTargetReference[] | No | The array of targets the responder request is being sent to |

