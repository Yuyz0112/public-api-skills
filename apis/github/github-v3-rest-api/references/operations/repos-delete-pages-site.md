# DELETE /repos/{owner}/{repo}/pages

**Resource:** [repos](../resources/repos.md)
**Delete a GitHub Pages site**
**Operation ID:** `repos/delete-pages-site`

Deletes a GitHub Pages site. For more information, see "[About GitHub Pages](/github/working-with-github-pages/about-github-pages).

The authenticated user must be a repository administrator, maintainer, or have the 'manage GitHub Pages settings' permission.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 404 | (reference) |
| 409 | (reference) |
| 422 | (reference) |

