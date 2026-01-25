# POST /rest/api/3/field/{fieldId}/context/{contextId}/issuetype/remove

**Resource:** [Issue custom field contexts](../resources/Issue-custom-field-contexts.md)
**Remove issue types from context**
**Operation ID:** `removeIssueTypesFromContext`

Removes issue types from a custom field context.

A custom field context without any issue types applies to all issue types.

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

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
