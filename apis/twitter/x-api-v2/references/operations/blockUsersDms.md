# POST /2/users/{id}/dm/block

**Resource:** [Users](../resources/Users.md)
**Block DMs**
**Operation ID:** `blockUsersDms`

Blocks direct messages to or from a specific User by their ID for the authenticated user.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserId | Yes | The ID of the target User that the authenticated user requesting to block dms for. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[UsersDMBlockCreateResponse](../schemas/Users/UsersDMBlockCreateResponse.md)

## Security

- **OAuth2UserToken**: dm.write, tweet.read, users.read
- **UserToken**
