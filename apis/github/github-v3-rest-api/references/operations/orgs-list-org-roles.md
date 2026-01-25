# GET /orgs/{org}/organization-roles

**Resource:** [orgs](../resources/orgs.md)
**Get all organization roles for an organization**
**Operation ID:** `orgs/list-org-roles`

Lists the organization roles available in this organization. For more information on organization roles, see "[Using organization roles](https://docs.github.com/organizations/managing-peoples-access-to-your-organization-with-roles/using-organization-roles)."

To use this endpoint, the authenticated user must be one of:

- An administrator for the organization.
- A user, or a user on a team, with the fine-grained permissions of `read_organization_custom_org_role` in the organization.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response - list of organization roles |
| 404 | (reference) |
| 422 | (reference) |

