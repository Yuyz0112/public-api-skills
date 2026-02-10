# GET /api/v4/broadcast_messages

**Resource:** [Broadcast messages](../resources/Broadcast-messages.md)
**Get all broadcast messages**
**Operation ID:** `getApiV4BroadcastMessages`

This feature was introduced in GitLab 8.12.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSystemBroadcastMessage](../schemas/APIEntitiesSystemBroadcastMessage/APIEntitiesSystemBroadcastMessage.md)

