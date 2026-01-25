# DELETE /rest/api/3/field/{fieldId}/context/{contextId}

**Resource:** [Issue custom field contexts](../resources/Issue-custom-field-contexts.md)
**Delete custom field context**
**Operation ID:** `deleteCustomFieldContext`

Deletes a [ custom field context](https://confluence.atlassian.com/adminjiracloud/what-are-custom-field-contexts-991923859.html).

This API will not allow removing the global context from April 2026. See [CHANGE-3019](https://developer.atlassian.com/changelog/#CHANGE-3019)

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field. |
| `contextId` | path | integer (int64) | Yes | The ID of the context. |

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if the context is deleted. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the custom field or the context is not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
