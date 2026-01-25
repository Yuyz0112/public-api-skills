# POST /channels/{channel_id}/send-soundboard-sound

**Resource:** [channels](../resources/channels.md)
**Operation ID:** `send_soundboard_sound`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SoundboardSoundSendRequest](../schemas/Soundboard/SoundboardSoundSendRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | 204 response for send_soundboard_sound |
| 429 | (reference) |
| 4XX | (reference) |

## Security

- **BotToken**
