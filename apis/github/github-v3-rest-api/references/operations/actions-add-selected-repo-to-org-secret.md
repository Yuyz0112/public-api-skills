# PUT /orgs/{org}/actions/secrets/{secret_name}/repositories/{repository_id}

**Resource:** [actions](../resources/actions.md)
**Add selected repository to an organization secret**
**Operation ID:** `actions/add-selected-repo-to-org-secret`

Adds a repository to an organization secret when the `visibility` for
repository access is set to `selected`. For more information about setting the visibility, see [Create or
update an organization secret](https://docs.github.com/rest/actions/secrets#create-or-update-an-organization-secret).

Authenticated users must have collaborator access to a repository to create, update, or read secrets.

OAuth tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint. If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repository_id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content when repository was added to the selected list |
| 409 | Conflict when visibility type is not set to selected |

