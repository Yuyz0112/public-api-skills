# GET /2/dm_conversations/with/{participant_id}/dm_events

**Resource:** [Direct Messages](../resources/Direct-Messages.md)
**Get DM events for a DM conversation**
**Operation ID:** `getDirectMessagesEventsByParticipantId`

Retrieves direct message events for a specific conversation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `participant_id` | path | UserId | Yes | The ID of the participant user for the One to One DM conversation. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationToken32 | No | This parameter is used to get a specified 'page' of results. |
| `event_types` | query | string[] | No | The set of event_types to include in the results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2DmConversationsWithParticipantIdDmEventsResponse](../schemas/Get/Get2DmConversationsWithParticipantIdDmEventsResponse.md)

## Security

- **OAuth2UserToken**: dm.read, tweet.read, users.read
- **UserToken**
