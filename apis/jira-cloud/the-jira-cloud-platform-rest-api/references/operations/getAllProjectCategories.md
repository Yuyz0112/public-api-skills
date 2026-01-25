# GET /rest/api/3/projectCategory

**Resource:** [Project categories](../resources/Project-categories.md)
**Get all project categories**
**Operation ID:** `getAllProjectCategories`

Returns all project categories.

**[Permissions](#permissions) required:** Permission to access Jira.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |

**Success Response Schema:**

Array of [ProjectCategory](../schemas/Project/ProjectCategory.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
