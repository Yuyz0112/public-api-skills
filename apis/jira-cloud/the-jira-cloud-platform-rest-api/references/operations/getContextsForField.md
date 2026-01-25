# GET /rest/api/3/field/{fieldId}/context

**Resource:** [Issue custom field contexts](../resources/Issue-custom-field-contexts.md)
**Get custom field contexts**
**Operation ID:** `getContextsForField`

Returns a [paginated](#pagination) list of [ contexts](https://confluence.atlassian.com/adminjiracloud/what-are-custom-field-contexts-991923859.html) for a custom field. Contexts can be returned as follows:

 *  With no other parameters set, all contexts.
 *  By defining `id` only, all contexts from the list of IDs.
 *  By defining `isAnyIssueType`, limit the list of contexts returned to either those that apply to all issue types (true) or those that apply to only a subset of issue types (false)
 *  By defining `isGlobalContext`, limit the list of contexts return to either those that apply to all projects (global contexts) (true) or those that apply to only a subset of projects (false).

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg). *Edit Workflow* [edit workflow permission](https://support.atlassian.com/jira-cloud-administration/docs/permissions-for-company-managed-projects/#Edit-Workflows)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field. |
| `isAnyIssueType` | query | boolean | No | Whether to return contexts that apply to all issue types. |
| `isGlobalContext` | query | boolean | No | Whether to return contexts that apply to all projects. |
| `contextId` | query | integer[] | No | The list of context IDs. To include multiple contexts, separate IDs with ampersand: `contextId=10000&contextId=10001`. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the custom field was not found. |

**Success Response Schema:**

[PageBeanCustomFieldContext](../schemas/Page/PageBeanCustomFieldContext.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
