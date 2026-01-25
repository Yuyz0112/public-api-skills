# GET /repos/{owner}/{repo}/actions/permissions/fork-pr-contributor-approval

**Resource:** [actions](../resources/actions.md)
**Get fork PR contributor approval permissions for a repository**
**Operation ID:** `actions/get-fork-pr-contributor-approval-permissions-repository`

Gets the fork PR contributor approval policy for a repository.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[actions-fork-pr-contributor-approval](../schemas/actions-fork-pr-contributor-approval/actions-fork-pr-contributor-approval.md)

