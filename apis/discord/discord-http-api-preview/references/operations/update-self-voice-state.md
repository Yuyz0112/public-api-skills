# PATCH /guilds/{guild_id}/voice-states/@me

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `update_self_voice_state`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [UpdateSelfVoiceStateRequestPartial](../schemas/Update/UpdateSelfVoiceStateRequestPartial.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | 204 response for update_self_voice_state |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**
