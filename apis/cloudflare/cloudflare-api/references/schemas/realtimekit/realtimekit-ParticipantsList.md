# realtimekit_ParticipantsList

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_at` | string | No | timestamp when this participant was created. |
| `custom_participant_id` | string | No | ID passed by client to create this participant. |
| `display_name` | string | No | Display name of participant when joining the session. |
| `duration` | number | No | number of minutes for which the participant was in the session. |
| `id` | string | No | Participant ID. This maps to the corresponding peerId. |
| `joined_at` | string | No | timestamp at which participant joined the session. |
| `left_at` | string | No | timestamp at which participant left the session. |
| `preset_name` | string | No | Name of the preset associated with the participant. |
| `updated_at` | string | No | timestamp when this participant's data was last updated. |
| `user_id` | string | No | User id for this participant. |

