# GET /rest/api/3/project/{projectIdOrKey}/avatars

**Resource:** [Project avatars](../resources/Project-avatars.md)
**Get all project avatars**
**Operation ID:** `getAllProjectAvatars`

Returns all project avatars, grouped by system and custom avatars.

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Browse projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The ID or (case-sensitive) key of the project. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the project is not found or the user does not have permission to view the project. |

**Success Response Schema:**

[ProjectAvatars](../schemas/Project/ProjectAvatars.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work
