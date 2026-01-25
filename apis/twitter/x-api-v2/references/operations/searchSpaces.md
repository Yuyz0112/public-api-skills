# GET /2/spaces/search

**Resource:** [Spaces](../resources/Spaces.md)
**Search Spaces**
**Operation ID:** `searchSpaces`

Retrieves a list of Spaces matching the specified search query.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `query` | query | string | Yes | The search query. |
| `state` | query | enum: live, scheduled, all | No | The state of Spaces to search for. |
| `max_results` | query | integer (int32) | No | The number of results to return. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2SpacesSearchResponse](../schemas/Get/Get2SpacesSearchResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: space.read, tweet.read, users.read
