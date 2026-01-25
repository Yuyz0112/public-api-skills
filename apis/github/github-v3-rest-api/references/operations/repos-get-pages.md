# GET /repos/{owner}/{repo}/pages

**Resource:** [repos](../resources/repos.md)
**Get a GitHub Pages site**
**Operation ID:** `repos/get-pages`

Gets information about a GitHub Pages site.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[page](../schemas/page/page.md)

