# GET /rest/api/3/myself

**Resource:** [Myself](../resources/Myself.md)
**Get current user**
**Operation ID:** `getCurrentUser`

Returns details for the current user.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No | Use [expand](#expansion) to include additional information about user in the response. This parameter accepts a comma-separated list. Expand options include:

 *  `groups` Returns all groups, including nested groups, the user belongs to.
 *  `applicationRoles` Returns the application roles the user is assigned to. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

[User](../schemas/User/User.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-user
