# GET /2/dm_events

**Resource:** [Direct Messages](../resources/Direct-Messages.md)
**Get DM events**
**Operation ID:** `getDirectMessagesEvents`

Retrieves a list of recent direct message events across all conversations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationToken32 | No | This parameter is used to get a specified 'page' of results. |
| `event_types` | query | string[] | No | The set of event_types to include in the results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2DmEventsResponse](../schemas/Get/Get2DmEventsResponse.md)

## Security

- **OAuth2UserToken**: dm.read, tweet.read, users.read
- **UserToken**
