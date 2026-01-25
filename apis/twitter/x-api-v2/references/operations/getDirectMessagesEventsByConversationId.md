# GET /2/dm_conversations/{id}/dm_events

**Resource:** [Direct Messages](../resources/Direct-Messages.md)
**Get DM events for a DM conversation**
**Operation ID:** `getDirectMessagesEventsByConversationId`

Retrieves direct message events for a specific conversation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | DmConversationId | Yes | The DM conversation ID. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationToken32 | No | This parameter is used to get a specified 'page' of results. |
| `event_types` | query | string[] | No | The set of event_types to include in the results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2DmConversationsIdDmEventsResponse](../schemas/Get/Get2DmConversationsIdDmEventsResponse.md)

## Security

- **OAuth2UserToken**: dm.read, tweet.read, users.read
- **UserToken**
