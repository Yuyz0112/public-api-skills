# GET /orgs/{org}/actions/permissions/selected-actions

**Resource:** [actions](../resources/actions.md)
**Get allowed actions and reusable workflows for an organization**
**Operation ID:** `actions/get-allowed-actions-organization`

Gets the selected actions and reusable workflows that are allowed in an organization. To use this endpoint, the organization permission policy for `allowed_actions` must be configured to `selected`. For more information, see "[Set GitHub Actions permissions for an organization](#set-github-actions-permissions-for-an-organization)."

OAuth tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[selected-actions](../schemas/selected-actions/selected-actions.md)

