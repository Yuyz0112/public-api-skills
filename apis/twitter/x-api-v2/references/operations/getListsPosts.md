# GET /2/lists/{id}/tweets

**Resource:** [Lists](../resources/Lists.md)
**Get List Posts**
**Operation ID:** `getListsPosts`

Retrieves a list of Posts associated with a specific List by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | ListId | Yes | The ID of the List. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationToken36 | No | This parameter is used to get the next 'page' of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2ListsIdTweetsResponse](../schemas/Get/Get2ListsIdTweetsResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: list.read, tweet.read, users.read
- **UserToken**
