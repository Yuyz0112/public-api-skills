# PUT /orgs/{org}/actions/variables/{name}/repositories/{repository_id}

**Resource:** [actions](../resources/actions.md)
**Add selected repository to an organization variable**
**Operation ID:** `actions/add-selected-repo-to-org-variable`

Adds a repository to an organization variable that is available to selected repositories.
Organization variables that are available to selected repositories have their `visibility` field set to `selected`.

Authenticated users must have collaborator access to a repository to create, update, or read secrets.

OAuth tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repository_id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 409 | Response when the visibility of the variable is not set to `selected` |

