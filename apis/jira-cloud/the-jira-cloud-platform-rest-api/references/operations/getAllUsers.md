# GET /rest/api/3/users/search

**Resource:** [Users](../resources/Users.md)
**Get all users**
**Operation ID:** `getAllUsers`

Returns a list of all users, including active users, inactive users and previously deleted users that have an Atlassian account.

Privacy controls are applied to the response based on the users' preferences. This could mean, for example, that the user's email address is hidden. See the [Profile visibility overview](https://developer.atlassian.com/cloud/jira/platform/profile-visibility/) for more details.

**[Permissions](#permissions) required:** *Browse users and groups* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `startAt` | query | integer (int32) | No | The index of the first item to return. |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return (limited to 1000). |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 403 | Returned if the user doesn't have the necessary permission. |
| 409 | Returned if the request takes longer than 10 seconds or is interrupted. |

**Success Response Schema:**

Array of [User](../schemas/User/User.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
