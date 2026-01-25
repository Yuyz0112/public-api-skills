# PUT /orgs/{org}/actions/permissions/fork-pr-workflows-private-repos

**Resource:** [actions](../resources/actions.md)
**Set private repo fork PR workflow settings for an organization**
**Operation ID:** `actions/set-private-repo-fork-pr-workflows-settings-organization`

Sets the settings for whether workflows from fork pull requests can run on private repositories in an organization.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [actions-fork-pr-workflows-private-repos-request](../schemas/actions-fork-pr-workflows-private-repos-request/actions-fork-pr-workflows-private-repos-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Empty response for successful settings update |
| 403 | Forbidden - Fork PR workflow settings for private repositories are managed by the enterprise owner |
| 404 | (reference) |
| 422 | (reference) |

