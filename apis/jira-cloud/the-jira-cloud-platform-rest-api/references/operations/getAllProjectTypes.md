# GET /rest/api/3/project/type

**Resource:** [Project types](../resources/Project-types.md)
**Get all project types**
**Operation ID:** `getAllProjectTypes`

Returns all [project types](https://confluence.atlassian.com/x/Var1Nw), whether or not the instance has a valid license for each type.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** None.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect. |

**Success Response Schema:**

Array of [ProjectType](../schemas/Project/ProjectType.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
