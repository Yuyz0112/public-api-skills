# GET /rest/api/3/field/{fieldId}/context/defaultValue

**Resource:** [Issue custom field contexts](../resources/Issue-custom-field-contexts.md)
**Get custom field contexts default values**
**Operation ID:** `getDefaultValues`

Returns a [paginated](#pagination) list of defaults for a custom field. The results can be filtered by `contextId`, otherwise all values are returned. If no defaults are set for a context, nothing is returned.  
The returned object depends on type of the custom field:

 *  `CustomFieldContextDefaultValueDate` (type `datepicker`) for date fields.
 *  `CustomFieldContextDefaultValueDateTime` (type `datetimepicker`) for date-time fields.
 *  `CustomFieldContextDefaultValueSingleOption` (type `option.single`) for single choice select lists and radio buttons.
 *  `CustomFieldContextDefaultValueMultipleOption` (type `option.multiple`) for multiple choice select lists and checkboxes.
 *  `CustomFieldContextDefaultValueCascadingOption` (type `option.cascading`) for cascading select lists.
 *  `CustomFieldContextSingleUserPickerDefaults` (type `single.user.select`) for single users.
 *  `CustomFieldContextDefaultValueMultiUserPicker` (type `multi.user.select`) for user lists.
 *  `CustomFieldContextDefaultValueSingleGroupPicker` (type `grouppicker.single`) for single choice group pickers.
 *  `CustomFieldContextDefaultValueMultipleGroupPicker` (type `grouppicker.multiple`) for multiple choice group pickers.
 *  `CustomFieldContextDefaultValueURL` (type `url`) for URLs.
 *  `CustomFieldContextDefaultValueProject` (type `project`) for project pickers.
 *  `CustomFieldContextDefaultValueFloat` (type `float`) for floats (floating-point numbers).
 *  `CustomFieldContextDefaultValueLabels` (type `labels`) for labels.
 *  `CustomFieldContextDefaultValueTextField` (type `textfield`) for text fields.
 *  `CustomFieldContextDefaultValueTextArea` (type `textarea`) for text area fields.
 *  `CustomFieldContextDefaultValueReadOnly` (type `readonly`) for read only (text) fields.
 *  `CustomFieldContextDefaultValueMultipleVersion` (type `version.multiple`) for single choice version pickers.
 *  `CustomFieldContextDefaultValueSingleVersion` (type `version.single`) for multiple choice version pickers.

Forge custom fields [types](https://developer.atlassian.com/platform/forge/manifest-reference/modules/jira-custom-field-type/#data-types) are also supported, returning:

 *  `CustomFieldContextDefaultValueForgeStringFieldBean` (type `forge.string`) for Forge string fields.
 *  `CustomFieldContextDefaultValueForgeMultiStringFieldBean` (type `forge.string.list`) for Forge string collection fields.
 *  `CustomFieldContextDefaultValueForgeObjectFieldBean` (type `forge.object`) for Forge object fields.
 *  `CustomFieldContextDefaultValueForgeDateTimeFieldBean` (type `forge.datetime`) for Forge date-time fields.
 *  `CustomFieldContextDefaultValueForgeGroupFieldBean` (type `forge.group`) for Forge group fields.
 *  `CustomFieldContextDefaultValueForgeMultiGroupFieldBean` (type `forge.group.list`) for Forge group collection fields.
 *  `CustomFieldContextDefaultValueForgeNumberFieldBean` (type `forge.number`) for Forge number fields.
 *  `CustomFieldContextDefaultValueForgeUserFieldBean` (type `forge.user`) for Forge user fields.
 *  `CustomFieldContextDefaultValueForgeMultiUserFieldBean` (type `forge.user.list`) for Forge user collection fields.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fieldId` | path | string | Yes | The ID of the custom field, for example `customfield\_10000`. |
| `contextId` | query | integer[] | No | The IDs of the contexts. |
| `startAt` | query | integer (int64) | No | The index of the first item to return in a page of results (page offset). |
| `maxResults` | query | integer (int32) | No | The maximum number of items to return per page. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have the required permissions. |
| 404 | Returned if the custom field is not found. |

**Success Response Schema:**

[PageBeanCustomFieldContextDefaultValue](../schemas/Page/PageBeanCustomFieldContextDefaultValue.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
