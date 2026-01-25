# GET /dialog.open

**Resource:** [dialog](../resources/dialog.md)
**Operation ID:** `dialog_open`

Open a dialog with a user

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `none` |
| `dialog` | query | string | Yes | The dialog definition. This must be a JSON-encoded string. |
| `trigger_id` | query | string | Yes | Exchange a trigger to post to the user. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response is quite minimal. |
| default | Typical error response, before getting to any possible validation errors. |

## Security

- **slackAuth**: none
