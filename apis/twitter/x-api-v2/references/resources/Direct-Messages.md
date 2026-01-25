# Direct Messages

Endpoints related to retrieving, managing Direct Messages

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| POST | `/2/dm_conversations` | Create DM conversation | [View](../operations/createDirectMessagesConversation.md) |
| GET | `/2/dm_conversations/with/{participant_id}/dm_events` | Get DM events for a DM conversation | [View](../operations/getDirectMessagesEventsByParticipantId.md) |
| POST | `/2/dm_conversations/with/{participant_id}/messages` | Create DM message by participant ID | [View](../operations/createDirectMessagesByParticipantId.md) |
| POST | `/2/dm_conversations/{dm_conversation_id}/messages` | Create DM message by conversation ID | [View](../operations/createDirectMessagesByConversationId.md) |
| GET | `/2/dm_conversations/{id}/dm_events` | Get DM events for a DM conversation | [View](../operations/getDirectMessagesEventsByConversationId.md) |
| GET | `/2/dm_events` | Get DM events | [View](../operations/getDirectMessagesEvents.md) |
| GET | `/2/dm_events/{event_id}` | Get DM event by ID | [View](../operations/getDirectMessagesEventsById.md) |
| DELETE | `/2/dm_events/{event_id}` | Delete DM event | [View](../operations/deleteDirectMessagesEvents.md) |
