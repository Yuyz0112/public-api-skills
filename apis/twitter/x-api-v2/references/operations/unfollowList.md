# DELETE /2/users/{id}/followed_lists/{list_id}

**Resource:** [Lists](../resources/Lists.md)
**Unfollow List**
**Operation ID:** `unfollowList`

Causes the authenticated user to unfollow a specific List by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User that will unfollow the List. |
| `list_id` | path | ListId | Yes | The ID of the List to unfollow. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[ListFollowedResponse](../schemas/List/ListFollowedResponse.md)

## Security

- **OAuth2UserToken**: list.write, tweet.read, users.read
- **UserToken**
