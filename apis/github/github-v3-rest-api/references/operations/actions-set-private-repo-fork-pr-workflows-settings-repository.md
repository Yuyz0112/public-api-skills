# PUT /repos/{owner}/{repo}/actions/permissions/fork-pr-workflows-private-repos

**Resource:** [actions](../resources/actions.md)
**Set private repo fork PR workflow settings for a repository**
**Operation ID:** `actions/set-private-repo-fork-pr-workflows-settings-repository`

Sets the settings for whether workflows from fork pull requests can run on a private repository.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [actions-fork-pr-workflows-private-repos-request](../schemas/actions-fork-pr-workflows-private-repos-request/actions-fork-pr-workflows-private-repos-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Empty response for successful settings update |
| 404 | (reference) |
| 422 | (reference) |

