# DELETE /orgs/{org}/actions/secrets/{secret_name}/repositories/{repository_id}

**Resource:** [actions](../resources/actions.md)
**Remove selected repository from an organization secret**
**Operation ID:** `actions/remove-selected-repo-from-org-secret`

Removes a repository from an organization secret when the `visibility`
for repository access is set to `selected`. The visibility is set when you [Create
or update an organization secret](https://docs.github.com/rest/actions/secrets#create-or-update-an-organization-secret).

Authenticated users must have collaborator access to a repository to create, update, or read secrets.

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, the `repo` scope is also required.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repository_id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response when repository was removed from the selected list |
| 409 | Conflict when visibility type not set to selected |

