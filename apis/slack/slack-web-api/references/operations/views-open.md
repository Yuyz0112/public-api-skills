# GET /views.open

**Resource:** [views](../resources/views.md)
**Operation ID:** `views_open`

Open a view for a user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `none` |
| `trigger_id` | query | string | Yes | Exchange a trigger to post to the user. |
| `view` | query | string | Yes | A [view payload](/reference/surfaces/views). This must be a JSON-encoded string. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response includes the opened view payload. |
| default | Typical error response, before getting to any possible validation errors. |

## Security

- **slackAuth**: none
