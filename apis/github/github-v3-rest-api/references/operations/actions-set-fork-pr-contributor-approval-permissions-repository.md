# PUT /repos/{owner}/{repo}/actions/permissions/fork-pr-contributor-approval

**Resource:** [actions](../resources/actions.md)
**Set fork PR contributor approval permissions for a repository**
**Operation ID:** `actions/set-fork-pr-contributor-approval-permissions-repository`

Sets the fork PR contributor approval policy for a repository.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [actions-fork-pr-contributor-approval](../schemas/actions-fork-pr-contributor-approval/actions-fork-pr-contributor-approval.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |
| 422 | (reference) |

