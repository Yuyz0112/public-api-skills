# POST /rest/api/3/projectCategory

**Resource:** [Project categories](../resources/Project-categories.md)
**Create project category**
**Operation ID:** `createProjectCategory`

Creates a project category.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ProjectCategory](../schemas/Project/ProjectCategory.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the request is successful. |
| 400 | Returned if:

 *  `name` is not provided or exceeds 255 characters.
 *  `description` exceeds 1000 characters. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 409 | Returned if the project category name is in use. |

**Success Response Schema:**

[ProjectCategory](../schemas/Project/ProjectCategory.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
