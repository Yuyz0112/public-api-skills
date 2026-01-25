# GET /2/spaces/{id}

**Resource:** [Spaces](../resources/Spaces.md)
**Get space by ID**
**Operation ID:** `getSpacesById`

Retrieves details of a specific space by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the Space to be retrieved. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2SpacesIdResponse](../schemas/Get/Get2SpacesIdResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: space.read, tweet.read, users.read
