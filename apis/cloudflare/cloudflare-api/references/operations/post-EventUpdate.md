# POST /accounts/{account_id}/cloudforce-one/events/{event_id}

**Resource:** [Event](../resources/Event.md)
**Updates an event**
**Operation ID:** `post_EventUpdate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `event_id` | path | string | Yes | Event UUID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the updated event. |
| 400 | Bad Request. |

## Security

- **api_token**
