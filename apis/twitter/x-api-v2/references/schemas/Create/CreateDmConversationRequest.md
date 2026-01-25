# CreateDmConversationRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `conversation_type` | enum: Group | Yes | The conversation type that is being created. |
| `message` | [CreateMessageRequest](CreateMessageRequest.md) | Yes |  |
| `participant_ids` | [DmParticipants](DmParticipants.md) | Yes |  |

