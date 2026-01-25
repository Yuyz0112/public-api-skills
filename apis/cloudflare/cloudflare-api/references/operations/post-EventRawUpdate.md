# POST /accounts/{account_id}/cloudforce-one/events/{event_id}/raw/{raw_id}

**Resource:** [Event](../resources/Event.md)
**Updates a raw event**
**Operation ID:** `post_EventRawUpdate`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |
| `event_id` | path | string | Yes | Event UUID. |
| `raw_id` | path | string | Yes | Raw Event UUID. |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the uuid of the updated raw event and its data. |
| 400 | Bad Request. |

## Security

- **api_token**
