# GET /2/users/{id}/owned_lists

**Resource:** [Lists](../resources/Lists.md)
**Get owned Lists**
**Operation ID:** `getUsersOwnedLists`

Retrieves a list of Lists owned by a specific User by their ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserId | Yes | The ID of the User to lookup. |
| `max_results` | query | integer (int32) | No | The maximum number of results. |
| `pagination_token` | query | PaginationTokenLong | No | This parameter is used to get a specified 'page' of results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersIdOwnedListsResponse](../schemas/Get/Get2UsersIdOwnedListsResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: list.read, tweet.read, users.read
- **UserToken**
