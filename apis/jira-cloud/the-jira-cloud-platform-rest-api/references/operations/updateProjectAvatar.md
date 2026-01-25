# PUT /rest/api/3/project/{projectIdOrKey}/avatar

**Resource:** [Project avatars](../resources/Project-avatars.md)
**Set project avatar**
**Operation ID:** `updateProjectAvatar`

Sets the avatar displayed for a project.

Use [Load project avatar](#api-rest-api-3-project-projectIdOrKey-avatar2-post) to store avatars against the project, before using this operation to set the displayed avatar.

**[Permissions](#permissions) required:** *Administer projects* [project permission](https://confluence.atlassian.com/x/yodKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The ID or (case-sensitive) key of the project. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [Avatar](../schemas/Avatar/Avatar.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to administer the project. |
| 404 | Returned if the project or avatar is not found or the user does not have permission to view the project. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
