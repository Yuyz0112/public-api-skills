# POST /repos/{owner}/{repo}/pages

**Resource:** [repos](../resources/repos.md)
**Create a GitHub Pages site**
**Operation ID:** `repos/create-pages-site`

Configures a GitHub Pages site. For more information, see "[About GitHub Pages](/github/working-with-github-pages/about-github-pages)."

The authenticated user must be a repository administrator, maintainer, or have the 'manage GitHub Pages settings' permission.

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Response |
| 409 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[page](../schemas/page/page.md)

