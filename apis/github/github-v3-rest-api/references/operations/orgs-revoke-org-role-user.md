# DELETE /orgs/{org}/organization-roles/users/{username}/{role_id}

**Resource:** [orgs](../resources/orgs.md)
**Remove an organization role from a user**
**Operation ID:** `orgs/revoke-org-role-user`

Remove an organization role from a user. For more information on organization roles, see "[Using organization roles](https://docs.github.com/organizations/managing-peoples-access-to-your-organization-with-roles/using-organization-roles)."

The authenticated user must be an administrator for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

