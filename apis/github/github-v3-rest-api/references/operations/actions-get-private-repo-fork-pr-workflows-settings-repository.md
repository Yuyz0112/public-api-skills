# GET /repos/{owner}/{repo}/actions/permissions/fork-pr-workflows-private-repos

**Resource:** [actions](../resources/actions.md)
**Get private repo fork PR workflow settings for a repository**
**Operation ID:** `actions/get-private-repo-fork-pr-workflows-settings-repository`

Gets the settings for whether workflows from fork pull requests can run on a private repository.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[actions-fork-pr-workflows-private-repos](../schemas/actions-fork-pr-workflows-private-repos/actions-fork-pr-workflows-private-repos.md)

