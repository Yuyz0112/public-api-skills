# POST /rest/api/3/user

**Resource:** [Users](../resources/Users.md)
**Create user**
**Operation ID:** `createUser`

Creates a user. This resource is retained for legacy compatibility. As soon as a more suitable alternative is available this resource will be deprecated.

**Note:** This API does not support Forge apps.

If the user exists and has access to Jira, the operation returns a 201 status. If the user exists but does not have access to Jira, the operation returns a 400 status.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg). The caller has to be an **organization admin**.

## Request Body

Details about the user to be created.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [NewUserDetails](../schemas/New/NewUserDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if the request is invalid or the number of licensed users is exceeded. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |

**Success Response Schema:**

[User](../schemas/User/User.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
