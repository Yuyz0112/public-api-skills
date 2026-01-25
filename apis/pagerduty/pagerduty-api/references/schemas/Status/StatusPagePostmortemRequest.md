# StatusPagePostmortemRequest

Request to create/update a given Postmortem resource.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `type` | enum: status_page_post_postmortem | Yes | The type of the object returned by the API - in this case, a Status Page Post Postmortem. |
| `post` | object | Yes | Status Page Post |
| `message` | string | Yes | The message of the Postmortem (supports Rich-Text). |
| `notify_subscribers` | boolean | Yes | Whether or not subscribers of the Status Page should be notified about the Postmortem. |

## Nested Fields

### `post`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | Yes | Status page post unique identifier |
| `type` | string | No | A string that determines the schema of the object. |

