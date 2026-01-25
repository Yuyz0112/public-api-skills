# GET /repos/{owner}/{repo}/pages/deployments/{pages_deployment_id}

**Resource:** [repos](../resources/repos.md)
**Get the status of a GitHub Pages deployment**
**Operation ID:** `repos/get-pages-deployment`

Gets the current status of a GitHub Pages deployment.

The authenticated user must have read permission for the GitHub Pages site.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 404 | (reference) |

**Success Response Schema:**

[pages-deployment-status](../schemas/pages-deployment-status/pages-deployment-status.md)

