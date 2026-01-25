# GET /2/users/by

**Resource:** [Users](../resources/Users.md)
**Get Users by usernames**
**Operation ID:** `getUsersByUsernames`

Retrieves details of multiple Users by their usernames.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `usernames` | query | string[] | Yes | A list of usernames, comma-separated. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersByResponse](../schemas/Get/Get2UsersByResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**
