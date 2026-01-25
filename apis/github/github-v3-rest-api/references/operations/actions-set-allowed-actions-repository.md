# PUT /repos/{owner}/{repo}/actions/permissions/selected-actions

**Resource:** [actions](../resources/actions.md)
**Set allowed actions and reusable workflows for a repository**
**Operation ID:** `actions/set-allowed-actions-repository`

Sets the actions and reusable workflows that are allowed in a repository. To use this endpoint, the repository permission policy for `allowed_actions` must be configured to `selected`. For more information, see "[Set GitHub Actions permissions for a repository](#set-github-actions-permissions-for-a-repository)."

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Content Types:** `application/json`

**Schema:** [selected-actions](../schemas/selected-actions/selected-actions.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

