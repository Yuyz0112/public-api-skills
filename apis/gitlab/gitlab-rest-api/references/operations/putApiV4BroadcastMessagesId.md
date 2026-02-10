# PUT /api/v4/broadcast_messages/{id}

**Resource:** [Broadcast messages](../resources/Broadcast-messages.md)
**Update a broadcast message**
**Operation ID:** `putApiV4BroadcastMessagesId`

This feature was introduced in GitLab 8.12.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Broadcast message ID |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSystemBroadcastMessage](../schemas/APIEntitiesSystemBroadcastMessage/APIEntitiesSystemBroadcastMessage.md)

