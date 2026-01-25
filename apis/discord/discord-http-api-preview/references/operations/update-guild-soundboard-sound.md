# PATCH /guilds/{guild_id}/soundboard-sounds/{sound_id}

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `update_guild_soundboard_sound`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SoundboardPatchRequestPartial](../schemas/Soundboard/SoundboardPatchRequestPartial.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | 200 response for update_guild_soundboard_sound |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[SoundboardSoundResponse](../schemas/Soundboard/SoundboardSoundResponse.md)

## Security

- **BotToken**
