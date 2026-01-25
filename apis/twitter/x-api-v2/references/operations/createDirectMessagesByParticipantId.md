# POST /2/dm_conversations/with/{participant_id}/messages

**Resource:** [Direct Messages](../resources/Direct-Messages.md)
**Create DM message by participant ID**
**Operation ID:** `createDirectMessagesByParticipantId`

Sends a new direct message to a specific participant by their ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `participant_id` | path | UserId | Yes | The ID of the recipient user that will receive the DM. |

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
