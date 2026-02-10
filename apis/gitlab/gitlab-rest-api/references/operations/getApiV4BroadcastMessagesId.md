# GET /api/v4/broadcast_messages/{id}

**Resource:** [Broadcast messages](../resources/Broadcast-messages.md)
**Get a specific broadcast message**
**Operation ID:** `getApiV4BroadcastMessagesId`

This feature was introduced in GitLab 8.12.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Broadcast message ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSystemBroadcastMessage](../schemas/APIEntitiesSystemBroadcastMessage/APIEntitiesSystemBroadcastMessage.md)

