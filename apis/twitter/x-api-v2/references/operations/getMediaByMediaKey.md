# GET /2/media/{media_key}

**Resource:** [Media](../resources/Media.md)
**Get Media by media key**
**Operation ID:** `getMediaByMediaKey`

Retrieves details of a specific Media file by its media key.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `media_key` | path | MediaKey | Yes | A single Media Key. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2MediaMediaKeyResponse](../schemas/Get/Get2MediaMediaKeyResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read
- **UserToken**
