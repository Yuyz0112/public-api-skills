# PUT /rest/api/3/filter/defaultShareScope

**Resource:** [Filter sharing](../resources/Filter-sharing.md)
**Set default share scope**
**Operation ID:** `setDefaultShareScope`

Sets the default sharing for new filters and dashboards for a user.

**[Permissions](#permissions) required:** Permission to access Jira.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [DefaultShareScope](../schemas/Default/DefaultShareScope.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if an invalid scope is set. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[DefaultShareScope](../schemas/Default/DefaultShareScope.md)

## Security

- **basicAuth**
- **OAuth2**: write:jira-work
