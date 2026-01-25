# GET /2/spaces/{id}/buyers

**Resource:** [Spaces](../resources/Spaces.md)
**Get Space ticket buyers**
**Operation ID:** `getSpacesBuyers`

Retrieves a list of Users who purchased tickets to a specific Space by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the Space to be retrieved. |
| `pagination_token` | query | PaginationToken32 | No | This parameter is used to get a specified 'page' of results. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2SpacesIdBuyersResponse](../schemas/Get/Get2SpacesIdBuyersResponse.md)

## Security

- **OAuth2UserToken**: space.read, tweet.read, users.read
