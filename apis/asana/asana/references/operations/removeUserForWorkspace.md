# POST /workspaces/{workspace_gid}/removeUser

**Resource:** [Workspaces](../resources/Workspaces.md)
**Remove a user from a workspace or organization**
**Operation ID:** `removeUserForWorkspace`

Remove a user from a workspace or organization.

The user making this call must be an admin in the workspace. The user can
be referenced by their globally unique user ID or their email address.

When invoked using a **Service Account Token (SAT)**, this endpoint follows the same behavior as the
[SCIM API Delete endpoint](/docs/scim).
To learn more about how Asana handles user deprovisioning, refer to our
[Help Center article on deprovisioning users](https://help.asana.com/s/article/user-deprovisioning).

When invoked using a **Personal Access Token (PAT)**, the endpoint behaves similarly, except that
ownership of the user’s resources is transferred to the **PAT owner** instead of the admin
[specified in the Admin Console](https://help.asana.com/s/article/user-deprovisioning#gl-deprovisioning).

**Note:** If you wish to retain access to a user’s private resources
(i.e., those visible only to that user), you have to make them public manually
(or ask the user to do so) before removal.

Returns an empty data record.

## Request Body

The user to remove from the workspace.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The user was removed successfully to the workspace or organization. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
