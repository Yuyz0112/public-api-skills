# dependabot-alert-dismissal-request-simple

Information about an active dismissal request for this Dependabot alert.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No | The unique identifier of the dismissal request. |
| `status` | enum: pending, approved, rejected... | No | The current status of the dismissal request. |
| `requester` | object | No | The user who requested the dismissal. |
| `created_at` | string (date-time) | No | The date and time when the dismissal request was created. |
| `url` | string (uri) | No | The API URL to get more information about this dismissal request. |

## Nested Fields

### `requester`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No | The unique identifier of the user. |
| `login` | string | No | The login name of the user. |

