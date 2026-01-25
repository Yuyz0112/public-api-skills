# PUT /orgs/{org}/actions/variables/{name}/repositories

**Resource:** [actions](../resources/actions.md)
**Set selected repositories for an organization variable**
**Operation ID:** `actions/set-selected-repos-for-org-variable`

Replaces all repositories for an organization variable that is available
to selected repositories. Organization variables that are available to selected
repositories have their `visibility` field set to `selected`.

Authenticated users must have collaborator access to a repository to create, update, or read variables.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, the `repo` scope is also required.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 409 | Response when the visibility of the variable is not set to `selected` |

