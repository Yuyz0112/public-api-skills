# GET /repos/{owner}/{repo}/installation

**Resource:** [apps](../resources/apps.md)
**Get a repository installation for the authenticated app**
**Operation ID:** `apps/get-repo-installation`

Enables an authenticated GitHub App to find the repository's installation information. The installation's account type will be either an organization or a user account, depending which account the repository belongs to.

You must use a [JWT](https://docs.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 301 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[installation](../schemas/installation/installation.md)

