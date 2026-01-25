# POST /2/dm_conversations

**Resource:** [Direct Messages](../resources/Direct-Messages.md)
**Create DM conversation**
**Operation ID:** `createDirectMessagesConversation`

Initiates a new direct message conversation with specified participants.

## Request Body

**Content Types:** `application/json`

**Schema:** [CreateDmConversationRequest](../schemas/Create/CreateDmConversationRequest.md)

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
