# PUT /orgs/{org}/actions/permissions/selected-actions

**Resource:** [actions](../resources/actions.md)
**Set allowed actions and reusable workflows for an organization**
**Operation ID:** `actions/set-allowed-actions-organization`

Sets the actions and reusable workflows that are allowed in an organization. To use this endpoint, the organization permission policy for `allowed_actions` must be configured to `selected`. For more information, see "[Set GitHub Actions permissions for an organization](#set-github-actions-permissions-for-an-organization)."

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Request Body

**Content Types:** `application/json`

**Schema:** [selected-actions](../schemas/selected-actions/selected-actions.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

