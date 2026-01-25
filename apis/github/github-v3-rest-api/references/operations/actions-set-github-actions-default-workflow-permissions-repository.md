# PUT /repos/{owner}/{repo}/actions/permissions/workflow

**Resource:** [actions](../resources/actions.md)
**Set default workflow permissions for a repository**
**Operation ID:** `actions/set-github-actions-default-workflow-permissions-repository`

Sets the default workflow permissions granted to the `GITHUB_TOKEN` when running workflows in a repository, and sets if GitHub Actions
can submit approving pull request reviews.
For more information, see "[Setting the permissions of the GITHUB_TOKEN for your repository](https://docs.github.com/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-github-actions-settings-for-a-repository#setting-the-permissions-of-the-github_token-for-your-repository)."

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [actions-set-default-workflow-permissions](../schemas/actions-set-default-workflow-permissions/actions-set-default-workflow-permissions.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Success response |
| 409 | Conflict response when changing a setting is prevented by the owning organization |

