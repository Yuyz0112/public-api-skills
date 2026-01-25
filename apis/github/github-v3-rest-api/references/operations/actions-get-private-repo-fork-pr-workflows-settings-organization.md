# GET /orgs/{org}/actions/permissions/fork-pr-workflows-private-repos

**Resource:** [actions](../resources/actions.md)
**Get private repo fork PR workflow settings for an organization**
**Operation ID:** `actions/get-private-repo-fork-pr-workflows-settings-organization`

Gets the settings for whether workflows from fork pull requests can run on private repositories in an organization.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[actions-fork-pr-workflows-private-repos](../schemas/actions-fork-pr-workflows-private-repos/actions-fork-pr-workflows-private-repos.md)

