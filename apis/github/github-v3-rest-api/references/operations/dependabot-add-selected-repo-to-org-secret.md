# PUT /orgs/{org}/dependabot/secrets/{secret_name}/repositories/{repository_id}

**Resource:** [dependabot](../resources/dependabot.md)
**Add selected repository to an organization secret**
**Operation ID:** `dependabot/add-selected-repo-to-org-secret`

Adds a repository to an organization secret when the `visibility` for
repository access is set to `selected`. The visibility is set when you [Create or
update an organization secret](https://docs.github.com/rest/dependabot/secrets#create-or-update-an-organization-secret).

OAuth app tokens and personal access tokens (classic) need the `admin:org` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repository_id` | path | integer | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content when repository was added to the selected list |
| 409 | Conflict when visibility type is not set to selected |

