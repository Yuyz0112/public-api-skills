# Issue custom field options (apps)

This resource represents custom issue field select list options created by a Connect app. See [Issue custom field options](#api-group-Issue-custom-field-options) to manipulate options created in Jira or using the REST API.

A select list issue field is a type of [issue field](https://developer.atlassian.com/cloud/jira/platform/modules/issue-field/) that enables a user to select an option from a list. Use it to add, remove, and update the options of a select list issue field.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/field/{fieldKey}/option` | Get all issue field options | [View](../operations/getAllIssueFieldOptions.md) |
| POST | `/rest/api/3/field/{fieldKey}/option` | Create issue field option | [View](../operations/createIssueFieldOption.md) |
| GET | `/rest/api/3/field/{fieldKey}/option/suggestions/edit` | Get selectable issue field options | [View](../operations/getSelectableIssueFieldOptions.md) |
| GET | `/rest/api/3/field/{fieldKey}/option/suggestions/search` | Get visible issue field options | [View](../operations/getVisibleIssueFieldOptions.md) |
| GET | `/rest/api/3/field/{fieldKey}/option/{optionId}` | Get issue field option | [View](../operations/getIssueFieldOption.md) |
| PUT | `/rest/api/3/field/{fieldKey}/option/{optionId}` | Update issue field option | [View](../operations/updateIssueFieldOption.md) |
| DELETE | `/rest/api/3/field/{fieldKey}/option/{optionId}` | Delete issue field option | [View](../operations/deleteIssueFieldOption.md) |
| DELETE | `/rest/api/3/field/{fieldKey}/option/{optionId}/issue` | Replace issue field option | [View](../operations/replaceIssueFieldOption.md) |
