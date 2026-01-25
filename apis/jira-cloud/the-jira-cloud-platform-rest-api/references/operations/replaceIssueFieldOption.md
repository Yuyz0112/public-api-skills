# DELETE /rest/api/3/field/{fieldKey}/option/{optionId}/issue

**Resource:** [Issue custom field options (apps)](../resources/Issue-custom-field-options-apps.md)
**Replace issue field option**
**Operation ID:** `replaceIssueFieldOption`

Deselects an issue-field select-list option from all issues where it is selected. A different option can be selected to replace the deselected option. The update can also be limited to a smaller set of issues by using a JQL query.

Connect and Forge app users with *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg) can override the screen security configuration using `overrideScreenSecurity` and `overrideEditableFlag`.

This is an [asynchronous operation](#async). The response object contains a link to the long-running task.

Note that this operation **only works for issue field select list options added by Connect apps**, it cannot be used with issue field select list options created in Jira or using operations from the [Issue custom field options](#api-group-Issue-custom-field-options) resource.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg). Jira permissions are not required for the app providing the field.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `replaceWith` | query | integer (int64) | No | The ID of the option that will replace the currently selected option. |
| `jql` | query | string | No | A JQL query that specifies the issues to be updated. For example, *project=10000*. |
| `overrideScreenSecurity` | query | boolean | No | Whether screen security is overridden to enable hidden fields to be edited. Available to Connect and Forge app users with admin permission. |
| `overrideEditableFlag` | query | boolean | No | Whether screen security is overridden to enable uneditable fields to be edited. Available to Connect and Forge app users with *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg). |
| `fieldKey` | path | string | Yes | The field key is specified in the following format: **$(app-key)\_\_$(field-key)**. For example, *example-add-on\_\_example-issue-field*. To determine the `fieldKey` value, do one of the following:

 *  open the app's plugin descriptor, then **app-key** is the key at the top and **field-key** is the key in the `jiraIssueFields` module. **app-key** can also be found in the app listing in the Atlassian Universal Plugin Manager.
 *  run [Get fields](#api-rest-api-3-field-get) and in the field details the value is returned in `key`. For example, `"key": "teams-add-on__team-issue-field"` |
| `optionId` | path | integer (int64) | Yes | The ID of the option to be deselected. |

## Responses

| Status | Description |
|--------|-------------|
| 303 | Returned if the long-running task to deselect the option is started. |
| 400 | Returned if the request is not valid. |
| 403 | Returned if the user does not have the necessary permission. |
| 404 | Returned if the field is not found or does not support options, or the options to be replaced are not found. |

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
