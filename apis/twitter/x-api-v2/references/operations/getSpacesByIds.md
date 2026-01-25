# GET /2/spaces

**Resource:** [Spaces](../resources/Spaces.md)
**Get Spaces by IDs**
**Operation ID:** `getSpacesByIds`

Retrieves details of multiple Spaces by their IDs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ids` | query | string[] | Yes | The list of Space IDs to return. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2SpacesResponse](../schemas/Get/Get2SpacesResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: space.read, tweet.read, users.read
