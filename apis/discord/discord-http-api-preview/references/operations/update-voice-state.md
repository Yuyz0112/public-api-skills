# PATCH /guilds/{guild_id}/voice-states/{user_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `update_voice_state`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateVoiceStateRequestPartial](../schemas/Update/UpdateVoiceStateRequestPartial.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | 204 response for update_voice_state |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**
