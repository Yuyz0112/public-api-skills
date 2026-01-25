# DELETE /orgs/{org}/codespaces/secrets/{secret_name}/repositories/{repository_id}

**Resource:** [codespaces](../resources/codespaces.md)
**Remove selected repository from an organization secret**
**Operation ID:** `codespaces/remove-selected-repo-from-org-secret`

Removes a repository from an organization development environment secret when the `visibility`
for repository access is set to `selected`. The visibility is set when you [Create
or update an organization secret](https://docs.github.com/rest/codespaces/organization-secrets#create-or-update-an-organization-secret).

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repository_id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response when repository was removed from the selected list |
| 404 | (reference) |
| 409 | Conflict when visibility type not set to selected |
| 422 | (reference) |

