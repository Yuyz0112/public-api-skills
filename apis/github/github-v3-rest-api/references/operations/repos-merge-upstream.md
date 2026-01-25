# POST /repos/{owner}/{repo}/merge-upstream

**Resource:** [repos](../resources/repos.md)
**Sync a fork branch with the upstream repository**
**Operation ID:** `repos/merge-upstream`

Sync a branch of a forked repository to keep it up-to-date with the upstream repository.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | The branch has been successfully synced with the upstream repository |
| 409 | The branch could not be synced because of a merge conflict |
| 422 | The branch could not be synced for some other reason |

**Success Response Schema:**

[merged-upstream](../schemas/merged-upstream/merged-upstream.md)

