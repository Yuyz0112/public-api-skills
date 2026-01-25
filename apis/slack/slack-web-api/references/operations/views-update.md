# GET /views.update

**Resource:** [views](../resources/views.md)
**Operation ID:** `views_update`

Update an existing view.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `none` |
| `view_id` | query | string | No | A unique identifier of the view to be updated. Either `view_id` or `external_id` is required. |
| `external_id` | query | string | No | A unique identifier of the view set by the developer. Must be unique for all views on a team. Max length of 255 characters. Either `view_id` or `external_id` is required. |
| `view` | query | string | No | A [view object](/reference/surfaces/views). This must be a JSON-encoded string. |
| `hash` | query | string | No | A string that represents view state to protect against possible race conditions. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response includes the updated view payload. |
| default | Typical error response. |

## Security

- **slackAuth**: none
