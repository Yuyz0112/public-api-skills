# GET /repos/{owner}/{repo}/pages/builds/latest

**Resource:** [repos](../resources/repos.md)
**Get latest Pages build**
**Operation ID:** `repos/get-latest-pages-build`

Gets information about the single most recent build of a GitHub Pages site.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[page-build](../schemas/page-build/page-build.md)

