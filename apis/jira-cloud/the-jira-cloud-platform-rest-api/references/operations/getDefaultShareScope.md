# GET /rest/api/3/filter/defaultShareScope

**Resource:** [Filter sharing](../resources/Filter-sharing.md)
**Get default share scope**
**Operation ID:** `getDefaultShareScope`

Returns the default sharing settings for new filters and dashboards for a user.

**[Permissions](#permissions) required:** Permission to access Jira.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[DefaultShareScope](../schemas/Default/DefaultShareScope.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
