# DELETE /rest/api/3/role/{id}/actors

**Resource:** [Project role actors](../resources/Project-role-actors.md)
**Delete default actors from project role**
**Operation ID:** `deleteProjectRoleActorsFromRole`

Deletes the [default actors](#api-rest-api-3-resolution-get) from a project role. You may delete a group or user, but you cannot delete a group and a user in the same request.

Changing a project role's default actors does not affect project role members for projects already created.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer (int64) | Yes | The ID of the project role. Use [Get all project roles](#api-rest-api-3-role-get) to get a list of project role IDs. |
| `user` | query | string | No | The user account ID of the user to remove as a default actor. |
| `groupId` | query | string | No | The group ID of the group to be removed as a default actor. This parameter cannot be used with the `group` parameter. |
| `group` | query | string | No | The group name of the group to be removed as a default actor.This parameter cannot be used with the `groupId` parameter. As a group's name can change, use of `groupId` is recommended. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have administrative permissions. |
| 404 | Returned if the project role is not found. |

**Success Response Schema:**

[ProjectRole](../schemas/Project/ProjectRole.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
