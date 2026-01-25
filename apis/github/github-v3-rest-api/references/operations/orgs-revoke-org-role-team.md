# DELETE /orgs/{org}/organization-roles/teams/{team_slug}/{role_id}

**Resource:** [orgs](../resources/orgs.md)
**Remove an organization role from a team**
**Operation ID:** `orgs/revoke-org-role-team`

Removes an organization role from a team. For more information on organization roles, see "[Using organization roles](https://docs.github.com/organizations/managing-peoples-access-to-your-organization-with-roles/using-organization-roles)."

The authenticated user must be an administrator for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

