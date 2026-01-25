# GET /repos/{owner}/{repo}/actions/permissions/selected-actions

**Resource:** [actions](../resources/actions.md)
**Get allowed actions and reusable workflows for a repository**
**Operation ID:** `actions/get-allowed-actions-repository`

Gets the settings for selected actions and reusable workflows that are allowed in a repository. To use this endpoint, the repository policy for `allowed_actions` must be configured to `selected`. For more information, see "[Set GitHub Actions permissions for a repository](#set-github-actions-permissions-for-a-repository)."

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[selected-actions](../schemas/selected-actions/selected-actions.md)

