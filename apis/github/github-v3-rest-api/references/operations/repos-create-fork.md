# POST /repos/{owner}/{repo}/forks

**Resource:** [repos](../resources/repos.md)
**Create a fork**
**Operation ID:** `repos/create-fork`

Create a fork for the authenticated user.

> [!NOTE]
> Forking a Repository happens asynchronously. You may have to wait a short period of time before you can access the git objects. If this takes longer than 5 minutes, be sure to contact [GitHub Support](https://support.github.com/contact?tags=dotcom-rest-api).

> [!NOTE]
> Although this endpoint works with GitHub Apps, the GitHub App must be installed on the destination account with access to all repositories and on the source account with access to the source repository.

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 202 | Response |
| 400 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

