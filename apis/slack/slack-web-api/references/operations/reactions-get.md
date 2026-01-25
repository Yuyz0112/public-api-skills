# GET /reactions.get

**Resource:** [reactions](../resources/reactions.md)
**Operation ID:** `reactions_get`

Gets reactions for an item.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | query | string | Yes | Authentication token. Requires scope: `reactions:read` |
| `channel` | query | string | No | Channel where the message to get reactions for was posted. |
| `file` | query | string | No | File to get reactions for. |
| `file_comment` | query | string | No | File comment to get reactions for. |
| `full` | query | boolean | No | If true always return the complete reaction list. |
| `timestamp` | query | string | No | Timestamp of the message to get reactions for. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: reactions:read
