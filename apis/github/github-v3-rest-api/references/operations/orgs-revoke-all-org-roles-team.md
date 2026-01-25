# DELETE /orgs/{org}/organization-roles/teams/{team_slug}

**Resource:** [orgs](../resources/orgs.md)
**Remove all organization roles for a team**
**Operation ID:** `orgs/revoke-all-org-roles-team`

Removes all assigned organization roles from a team. For more information on organization roles, see "[Using organization roles](https://docs.github.com/organizations/managing-peoples-access-to-your-organization-with-roles/using-organization-roles)."

The authenticated user must be an administrator for the organization to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

