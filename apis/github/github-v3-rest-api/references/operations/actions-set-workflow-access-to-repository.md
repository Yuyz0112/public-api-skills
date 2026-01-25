# PUT /repos/{owner}/{repo}/actions/permissions/access

**Resource:** [actions](../resources/actions.md)
**Set the level of access for workflows outside of the repository**
**Operation ID:** `actions/set-workflow-access-to-repository`

Sets the level of access that workflows outside of the repository have to actions and reusable workflows in the repository.
This endpoint only applies to private repositories.
For more information, see "[Allowing access to components in a private repository](https://docs.github.com/repositories/managing-your-repositorys-settings-and-features/enabling-features-for-your-repository/managing-github-actions-settings-for-a-repository#allowing-access-to-components-in-a-private-repository)".

OAuth app tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [actions-workflow-access-to-repository](../schemas/actions-workflow-access-to-repository/actions-workflow-access-to-repository.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |

