# DELETE /rest/api/3/project/{projectIdOrKey}/role/{id}

**Resource:** [Project role actors](../resources/Project-role-actors.md)
**Delete actors from project role**
**Operation ID:** `deleteActor`

Deletes actors from a project role for the project.

To remove default actors from the project role, use [Delete default actors from project role](#api-rest-api-3-role-id-actors-delete).

This operation can be accessed anonymously.

**[Permissions](#permissions) required:** *Administer Projects* [project permission](https://confluence.atlassian.com/x/yodKLg) for the project or *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `projectIdOrKey` | path | string | Yes | The project ID or project key (case sensitive). |
| `id` | path | integer (int64) | Yes | The ID of the project role. Use [Get all project roles](#api-rest-api-3-role-get) to get a list of project role IDs. |
| `user` | query | string | No | The user account ID of the user to remove from the project role. |
| `group` | query | string | No | The name of the group to remove from the project role. This parameter cannot be used with the `groupId` parameter. As a group's name can change, use of `groupId` is recommended. |
| `groupId` | query | string | No | The ID of the group to remove from the project role. This parameter cannot be used with the `group` parameter. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 404 | Returned if:

 *  the project or project role is not found.
 *  the calling user does not have administrative permission. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-project
