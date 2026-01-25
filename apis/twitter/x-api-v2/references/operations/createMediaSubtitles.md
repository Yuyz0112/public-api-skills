# POST /2/media/subtitles

**Resource:** [Media](../resources/Media.md)
**Create Media subtitles**
**Operation ID:** `createMediaSubtitles`

Creates subtitles for a specific Media file.

## Request Body

**Content Types:** `application/json`

**Schema:** [SubtitlesCreateRequest](../schemas/Subtitles/SubtitlesCreateRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[SubtitlesCreateResponse](../schemas/Subtitles/SubtitlesCreateResponse.md)

## Security

- **OAuth2UserToken**: media.write
- **UserToken**
