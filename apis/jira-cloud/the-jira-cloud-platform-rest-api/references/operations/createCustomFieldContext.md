# POST /rest/api/3/field/{fieldId}/context

**Resource:** [Issue custom field contexts](../resources/Issue-custom-field-contexts.md)
**Create custom field context**
**Operation ID:** `createCustomFieldContext`

Creates a custom field context.

If `projectIds` is empty, a global context is created. A global context is one that applies to all project. If `issueTypeIds` is empty, the context applies to all issue types.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateCustomFieldContext](../schemas/Create/CreateCustomFieldContext.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the custom field context is created. |
| 400 | Returned if the request is invalid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if the field, project, or issue type is not found. |
| 409 | Returned if the issue type is a sub-task, but sub-tasks are disabled in Jira settings. |

**Success Response Schema:**

[CreateCustomFieldContext](../schemas/Create/CreateCustomFieldContext.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
