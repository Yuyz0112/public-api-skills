# POST /2/users/{id}/followed_lists

**Resource:** [Lists](../resources/Lists.md)
**Follow List**
**Operation ID:** `followList`

Causes the authenticated user to follow a specific List by its ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | UserIdMatchesAuthenticatedUser | Yes | The ID of the authenticated source User that will follow the List. |

## Request Body

**Content Types:** `application/json`

**Schema:** [ListFollowedRequest](../schemas/List/ListFollowedRequest.md)

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
