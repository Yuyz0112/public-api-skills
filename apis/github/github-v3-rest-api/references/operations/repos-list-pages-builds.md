# GET /repos/{owner}/{repo}/pages/builds

**Resource:** [repos](../resources/repos.md)
**List GitHub Pages builds**
**Operation ID:** `repos/list-pages-builds`

Lists builts of a GitHub Pages site.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [page-build](../schemas/page-build/page-build.md)

