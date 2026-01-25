# GET /2/users/{id}/pinned_lists

**Resource:** [Lists](../resources/Lists.md)
**Get pinned Lists**
**Operation ID:** `getUsersPinnedLists`

Retrieves a list of Lists pinned by the authenticated user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User for whom to return results. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersIdPinnedListsResponse](../schemas/Get/Get2UsersIdPinnedListsResponse.md)

## Security

- **OAuth2UserToken**: list.read, tweet.read, users.read
- **UserToken**
