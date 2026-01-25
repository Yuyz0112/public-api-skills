# GET /2/spaces/{id}/tweets

**Resource:** [Spaces](../resources/Spaces.md)
**Get Space Posts**
**Operation ID:** `getSpacesPosts`

Retrieves a list of Posts shared in a specific Space by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the Space to be retrieved. |
| `max_results` | query | integer (int32) | No | The number of Posts to fetch from the provided space. If not provided, the value will default to the maximum of 100. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2SpacesIdTweetsResponse](../schemas/Get/Get2SpacesIdTweetsResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: space.read, tweet.read, users.read
