# GET /views.push

**Resource:** [views](../resources/views.md)
**Operation ID:** `views_push`

Push a view onto the stack of a root view.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `none` |
| `trigger_id` | query | string | Yes | Exchange a trigger to post to the user. |
| `view` | query | string | Yes | A [view payload](/reference/surfaces/views). This must be a JSON-encoded string. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response includes the pushed view payload. |
| default | Typical error response. |

## Security

- **slackAuth**: none
