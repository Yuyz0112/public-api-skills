# POST /rest/api/3/field/{fieldId}/context/{contextId}/project/remove

**Resource:** [Issue custom field contexts](../resources/Issue-custom-field-contexts.md)
**Remove custom field context from projects**
**Operation ID:** `removeCustomFieldContextFromProjects`

Removes a custom field context from projects.

A custom field context without any projects applies to all projects. Removing all projects from a custom field context would result in it applying to all projects.

If any project in the request is not assigned to the context, or the operation would result in two global contexts for the field, the operation fails.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field. |
| `contextId` | path | integer (int64) | Yes | The ID of the context. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ProjectIds](../schemas/Project/ProjectIds.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the custom field context is removed from the projects. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the custom field, context, or one or more projects are not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
