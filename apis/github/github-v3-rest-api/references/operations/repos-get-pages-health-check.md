# GET /repos/{owner}/{repo}/pages/health

**Resource:** [repos](../resources/repos.md)
**Get a DNS health check for GitHub Pages**
**Operation ID:** `repos/get-pages-health-check`

Gets a health check of the DNS settings for the `CNAME` record configured for a repository's GitHub Pages.

The first request to this endpoint returns a `202 Accepted` status and starts an asynchronous background task to get the results for the domain. After the background task completes, subsequent requests to this endpoint return a `200 OK` status with the health check results in the response.

The authenticated user must be a repository administrator, maintainer, or have the 'manage GitHub Pages settings' permission to use this endpoint.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 202 | Empty response |
| 400 | Custom domains are not available for GitHub Pages |
| 404 | (reference) |
| 422 | There isn't a CNAME for this page |

**Success Response Schema:**

[pages-health-check](../schemas/pages-health-check/pages-health-check.md)

