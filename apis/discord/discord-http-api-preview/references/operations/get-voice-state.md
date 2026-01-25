# GET /guilds/{guild_id}/voice-states/{user_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `get_voice_state`

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for get_voice_state |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[VoiceStateResponse](../schemas/Voice/VoiceStateResponse.md)

## Security

- **BotToken**
