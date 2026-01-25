# GET /rest/api/3/field/{fieldId}/context/{contextId}/option

**Resource:** [Issue custom field options](../resources/Issue-custom-field-options.md)
**Get custom field options (context)**
**Operation ID:** `getOptionsForContext`

Returns a [paginated](#pagination) list of all custom field option for a context. Options are returned first then cascading options, in the order they display in Jira.

This operation works for custom field options created in Jira or the operations from this resource. **To work with issue field select list options created for Connect apps use the [Issue custom field options (apps)](#api-group-issue-custom-field-options--apps-) operations.**

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg). *Edit Workflow* [edit workflow permission](https://support.atlassian.com/jira-cloud-administration/docs/permissions-for-company-managed-projects/#Edit-Workflows)

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field. |
| `contextId` | path | integer (int64) | Yes | The ID of the context. |
| `optionId` | query | integer (int64) | No | The ID of the option. |
| `onlyOptions` | query | boolean | No | Whether only options are returned. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is not valid. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the custom field is not found or the context doesn't match the custom field. |

**Success Response Schema:**

[PageBeanCustomFieldContextOption](../schemas/Page/PageBeanCustomFieldContextOption.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
