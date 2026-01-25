# StatusPagePostmortem

A Postmortem represents a communication resource presented in the Status Page about follow-up made to a certain Post.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No | An unique identifier within Status Page scope that defines a single Postmortem resource. |
| `self` | string | No | The API resource URL of the Postmortem. |
| `post` | object | No | Status Page Post |
| `message` | string | No | The message of the Postmortem (supports Rich-Text). |
| `notify_subscribers` | boolean | No | Whether or not subscribers of the Status Page should be notified about the Postmortem. |
| `reported_at` | string (date-time) | No | The date and time the Postmortem was reported. |
| `type` | string | No | The type of the object returned by the API - in this case, a Status Page Post Postmortem. |

## Nested Fields

### `post`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | The id of the status page post. |
| `type` | string | No | A string that determines the schema of the object. |

