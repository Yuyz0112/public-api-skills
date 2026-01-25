# PUT /rest/api/3/field/{fieldId}/context/{contextId}/issuetype

**Resource:** [Issue custom field contexts](../resources/Issue-custom-field-contexts.md)
**Add issue types to context**
**Operation ID:** `addIssueTypesToContext`

Adds issue types to a custom field context, appending the issue types to the issue types list.

A custom field context without any issue types applies to all issue types. Adding issue types to such a custom field context would result in it applying to only the listed issue types.

If any of the issue types exists in the custom field context, the operation fails and no issue types are added.

This API will not allow adding issue types to the global context from April 2026. See [CHANGE-3019](https://developer.atlassian.com/changelog/#CHANGE-3019)

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field. |
| `contextId` | path | integer (int64) | Yes | The ID of the context. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [IssueTypeIds](../schemas/Issue/IssueTypeIds.md)

## Responses

| Status | Description |
|--------|-------------|
| 204 | Returned if operation is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the custom field, context, or one or more issue types are not found. |
| 409 | Returned if the issue type is a sub-task, but sub-tasks are disabled in Jira settings. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
