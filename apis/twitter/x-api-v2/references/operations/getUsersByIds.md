# GET /2/users

**Resource:** [Users](../resources/Users.md)
**Get Users by IDs**
**Operation ID:** `getUsersByIds`

Retrieves details of multiple Users by their IDs.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `ids` | query | UserId[] | Yes | A list of User IDs, comma-separated. You can specify up to 100 IDs. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersResponse](../schemas/Get/Get2UsersResponse.md)

## Security

- **BearerToken**
- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**
