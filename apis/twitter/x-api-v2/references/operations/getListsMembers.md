# GET /2/lists/{id}/members

**Resource:** [Lists](../resources/Lists.md)
**Get List members**
**Operation ID:** `getListsMembers`

Retrieves a list of Users who are members of a specific List by its ID.

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

[Get2ListsIdMembersResponse](../schemas/Get/Get2ListsIdMembersResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: list.read, tweet.read, users.read
- **UserToken**
