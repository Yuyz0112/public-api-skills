# PUT /rest/api/3/field/{fieldId}/context/{contextId}/project

**Resource:** [Issue custom field contexts](../resources/Issue-custom-field-contexts.md)
**Assign custom field context to projects**
**Operation ID:** `assignProjectsToCustomFieldContext`

Assigns a custom field context to projects.

If any project in the request is assigned to any context of the custom field, the operation fails.

This API will not allow adding projects to the global context from April 2026. See [CHANGE-3019](https://developer.atlassian.com/changelog/#CHANGE-3019)

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
| 204 | Returned if operation is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the custom field, context, or project is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
