# POST /repos/{owner}/{repo}/pages/deployments

**Resource:** [repos](../resources/repos.md)
**Create a GitHub Pages deployment**
**Operation ID:** `repos/create-pages-deployment`

Create a GitHub Pages deployment for a repository.

The authenticated user must have write permission to the repository.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 400 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[page-deployment](../schemas/page-deployment/page-deployment.md)

