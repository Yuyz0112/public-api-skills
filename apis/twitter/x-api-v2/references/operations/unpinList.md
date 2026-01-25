# DELETE /2/users/{id}/pinned_lists/{list_id}

**Resource:** [Lists](../resources/Lists.md)
**Unpin List**
**Operation ID:** `unpinList`

Causes the authenticated user to unpin a specific List by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User for whom to return results. |
| `list_id` | path | ListId | Yes | The ID of the List to unpin. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[ListUnpinResponse](../schemas/List/ListUnpinResponse.md)

## Security

- **OAuth2UserToken**: list.write, tweet.read, users.read
- **UserToken**
