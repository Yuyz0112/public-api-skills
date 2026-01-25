# GET /emoji.list

**Resource:** [emoji](../resources/emoji.md)
**Operation ID:** `emoji_list`

Lists custom emoji for a team.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `emoji:read` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: emoji:read
