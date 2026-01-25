# PUT /rest/api/3/projectCategory/{id}

**Resource:** [Project categories](../resources/Project-categories.md)
**Update project category**
**Operation ID:** `updateProjectCategory`

Updates a project category.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ProjectCategory](../schemas/Project/ProjectCategory.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if:

 *  `name` has been modified and exceeds 255 characters.
 *  `description` has been modified and exceeds 1000 characters. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the project category is not found. |

**Success Response Schema:**

[UpdatedProjectCategory](../schemas/Updated/UpdatedProjectCategory.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
