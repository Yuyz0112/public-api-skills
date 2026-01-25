# PUT /orgs/{org}/organization-roles/users/{username}/{role_id}

**Resource:** [orgs](../resources/orgs.md)
**Assign an organization role to a user**
**Operation ID:** `orgs/assign-user-to-org-role`

Assigns an organization role to a member of an organization. For more information on organization roles, see "[Using organization roles](https://docs.github.com/organizations/managing-peoples-access-to-your-organization-with-roles/using-organization-roles)."

The authenticated user must be an administrator for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | Response if the organization, user or role does not exist. |
| 422 | Response if the organization roles feature is not enabled enabled for the organization, the validation failed, or the user is not an organization member. |

