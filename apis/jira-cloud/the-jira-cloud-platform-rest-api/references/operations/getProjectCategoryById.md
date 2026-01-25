# GET /rest/api/3/projectCategory/{id}

**Resource:** [Project categories](../resources/Project-categories.md)
**Get project category by ID**
**Operation ID:** `getProjectCategoryById`

Returns a project category.

**[Permissions](#permissions) required:** Permission to access Jira.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the project category. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project category is not found. |

**Success Response Schema:**

[ProjectCategory](../schemas/Project/ProjectCategory.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
