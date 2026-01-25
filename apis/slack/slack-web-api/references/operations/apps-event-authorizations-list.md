# GET /apps.event.authorizations.list

**Resource:** [apps.event.authorizations](../resources/apps-event-authorizations.md)
**Operation ID:** `apps_event_authorizations_list`

Get a list of authorizations for the given event context. Each authorization represents an app installation that the event is visible to.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `token` | header | string | Yes | Authentication token. Requires scope: `authorizations:read` |
| `event_context` | query | string | Yes |  |
| `cursor` | query | string | No |  |
| `limit` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Typical success response |
| default | Typical error response |

## Security

- **slackAuth**: authorizations:read
