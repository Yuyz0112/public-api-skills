# POST /2/dm_conversations/{dm_conversation_id}/messages

**Resource:** [Direct Messages](../resources/Direct-Messages.md)
**Create DM message by conversation ID**
**Operation ID:** `createDirectMessagesByConversationId`

Sends a new direct message to a specific conversation by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dm_conversation_id` | path | string | Yes | The DM Conversation ID. |

## Request Body

**Content Types:** `application/json`

**Schema:** [CreateMessageRequest](../schemas/Create/CreateMessageRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[CreateDmEventResponse](../schemas/Create/CreateDmEventResponse.md)

## Security

- **OAuth2UserToken**: dm.write, tweet.read, users.read
- **UserToken**
