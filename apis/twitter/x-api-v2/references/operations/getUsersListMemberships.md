# GET /2/users/{id}/list_memberships

**Resource:** [Lists](../resources/Lists.md)
**Get List memberships**
**Operation ID:** `getUsersListMemberships`

Retrieves a list of Lists that a specific User is a member of by their ID.

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

[Get2UsersIdListMembershipsResponse](../schemas/Get/Get2UsersIdListMembershipsResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: list.read, tweet.read, users.read
- **UserToken**
