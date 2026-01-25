# POST /2/users/{id}/dm/unblock

**Resource:** [Users](../resources/Users.md)
**Unblock DMs**
**Operation ID:** `unblockUsersDms`

Unblocks direct messages to or from a specific User by their ID for the authenticated user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserId | Yes | The ID of the target User that the authenticated user requesting to unblock dms for. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[UsersDMUnBlockCreateResponse](../schemas/Users/UsersDMUnBlockCreateResponse.md)

## Security

- **OAuth2UserToken**: dm.write, tweet.read, users.read
- **UserToken**
