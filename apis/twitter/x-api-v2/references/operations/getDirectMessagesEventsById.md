# GET /2/dm_events/{event_id}

**Resource:** [Direct Messages](../resources/Direct-Messages.md)
**Get DM event by ID**
**Operation ID:** `getDirectMessagesEventsById`

Retrieves details of a specific direct message event by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `event_id` | path | DmEventId | Yes | dm event id. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2DmEventsEventIdResponse](../schemas/Get/Get2DmEventsEventIdResponse.md)

## Security

- **OAuth2UserToken**: dm.read, tweet.read, users.read
- **UserToken**
