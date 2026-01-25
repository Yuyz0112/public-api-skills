# GET /2/lists/{id}/followers

**Resource:** [Lists](../resources/Lists.md)
**Get List followers**
**Operation ID:** `getListsFollowers`

Retrieves a list of Users who follow a specific List by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | ListId | Yes | The ID of the List. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationTokenLong | No | This parameter is used to get a specified 'page' of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2ListsIdFollowersResponse](../schemas/Get/Get2ListsIdFollowersResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: list.read, tweet.read, users.read
- **UserToken**
