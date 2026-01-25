# GET /2/media

**Resource:** [Media](../resources/Media.md)
**Get Media by media keys**
**Operation ID:** `getMediaByMediaKeys`

Retrieves details of Media files by their media keys.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `media_keys` | query | MediaKey[] | Yes | A comma separated list of Media Keys. Up to 100 are allowed in a single request. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2MediaResponse](../schemas/Get/Get2MediaResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read
- **UserToken**
