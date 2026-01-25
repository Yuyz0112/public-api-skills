# GET /views.publish

**Resource:** [views](../resources/views.md)
**Operation ID:** `views_publish`

Publish a static view for a User.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `none` |
| `user_id` | query | string | Yes | `id` of the user you want publish a view to. |
| `view` | query | string | Yes | A [view payload](/reference/surfaces/views). This must be a JSON-encoded string. |
| `hash` | query | string | No | A string that represents view state to protect against possible race conditions. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response includes the published view payload. |
| default | Typical error response, before getting to any possible validation errors. |

## Security

- **slackAuth**: none
