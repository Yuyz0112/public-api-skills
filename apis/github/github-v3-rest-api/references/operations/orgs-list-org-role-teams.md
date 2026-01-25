# GET /orgs/{org}/organization-roles/{role_id}/teams

**Resource:** [orgs](../resources/orgs.md)
**List teams that are assigned to an organization role**
**Operation ID:** `orgs/list-org-role-teams`

Lists the teams that are assigned to an organization role. For more information on organization roles, see "[Using organization roles](https://docs.github.com/organizations/managing-peoples-access-to-your-organization-with-roles/using-organization-roles)."

To use this endpoint, you must be an administrator for the organization.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response - List of assigned teams |
| 404 | Response if the organization or role does not exist. |
| 422 | Response if the organization roles feature is not enabled or validation failed. |

**Success Response Schema:**

Array of [team-role-assignment](../schemas/team-role-assignment/team-role-assignment.md)

