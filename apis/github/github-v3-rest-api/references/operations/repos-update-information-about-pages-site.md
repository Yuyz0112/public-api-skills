# PUT /repos/{owner}/{repo}/pages

**Resource:** [repos](../resources/repos.md)
**Update information about a GitHub Pages site**
**Operation ID:** `repos/update-information-about-pages-site`

Updates information for a GitHub Pages site. For more information, see "[About GitHub Pages](/github/working-with-github-pages/about-github-pages).

The authenticated user must be a repository administrator, maintainer, or have the 'manage GitHub Pages settings' permission.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 400 | (reference) |
| 409 | (reference) |
| 422 | (reference) |

