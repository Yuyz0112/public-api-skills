# POST /guilds/{guild_id}/soundboard-sounds

**Resource:** [guilds](../resources/guilds.md)
**Operation ID:** `create_guild_soundboard_sound`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SoundboardCreateRequest](../schemas/Soundboard/SoundboardCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | 201 response for create_guild_soundboard_sound |
| 429 | (reference) |
| 4XX | (reference) |

**Success Response Schema:**

[SoundboardSoundResponse](../schemas/Soundboard/SoundboardSoundResponse.md)

## Security

- **BotToken**
