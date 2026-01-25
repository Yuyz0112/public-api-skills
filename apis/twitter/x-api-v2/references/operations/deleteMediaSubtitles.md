# DELETE /2/media/subtitles

**Resource:** [Media](../resources/Media.md)
**Delete Media subtitles**
**Operation ID:** `deleteMediaSubtitles`

Deletes subtitles for a specific Media file.

## Request Body

**Content Types:** `application/json`

**Schema:** [SubtitlesDeleteRequest](../schemas/Subtitles/SubtitlesDeleteRequest.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[SubtitlesDeleteResponse](../schemas/Subtitles/SubtitlesDeleteResponse.md)

## Security

- **OAuth2UserToken**: media.write
- **UserToken**
