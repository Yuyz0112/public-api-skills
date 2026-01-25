# DELETE /rest/api/3/projectCategory/{id}

**Resource:** [Project categories](../resources/Project-categories.md)
**Delete project category**
**Operation ID:** `removeProjectCategory`

Deletes a project category.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | ID of the project category to delete. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the project category is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
