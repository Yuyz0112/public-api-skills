# DELETE /orgs/{org}/actions/variables/{name}/repositories/{repository_id}

**Resource:** [actions](../resources/actions.md)
**Remove selected repository from an organization variable**
**Operation ID:** `actions/remove-selected-repo-from-org-variable`

Removes a repository from an organization variable that is
available to selected repositories. Organization variables that are available to
selected repositories have their `visibility` field set to `selected`.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, the `repo` scope is also required.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repository_id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 409 | Response when the visibility of the variable is not set to `selected` |

