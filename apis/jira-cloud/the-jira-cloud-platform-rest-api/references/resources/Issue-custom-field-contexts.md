# Issue custom field contexts

This resource represents issue custom field contexts. Use it to:

 *  get, create, update, and delete custom field contexts.
 *  get context to issue types and projects mappings.
 *  get custom field contexts for projects and issue types.
 *  assign custom field contexts to projects.
 *  remove custom field contexts from projects.
 *  add issue types to custom field contexts.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/field/{fieldId}/context` | Get custom field contexts | [View](../operations/getContextsForField.md) |
| POST | `/rest/api/3/field/{fieldId}/context` | Create custom field context | [View](../operations/createCustomFieldContext.md) |
| GET | `/rest/api/3/field/{fieldId}/context/defaultValue` | Get custom field contexts default values | [View](../operations/getDefaultValues.md) |
| PUT | `/rest/api/3/field/{fieldId}/context/defaultValue` | Set custom field contexts default values | [View](../operations/setDefaultValues.md) |
| GET | `/rest/api/3/field/{fieldId}/context/issuetypemapping` | Get issue types for custom field context | [View](../operations/getIssueTypeMappingsForContexts.md) |
| POST | `/rest/api/3/field/{fieldId}/context/mapping` | Get custom field contexts for projects and issue types | [View](../operations/getCustomFieldContextsForProjectsAndIssueTypes.md) |
| GET | `/rest/api/3/field/{fieldId}/context/projectmapping` | Get project mappings for custom field context | [View](../operations/getProjectContextMapping.md) |
| PUT | `/rest/api/3/field/{fieldId}/context/{contextId}` | Update custom field context | [View](../operations/updateCustomFieldContext.md) |
| DELETE | `/rest/api/3/field/{fieldId}/context/{contextId}` | Delete custom field context | [View](../operations/deleteCustomFieldContext.md) |
| PUT | `/rest/api/3/field/{fieldId}/context/{contextId}/issuetype` | Add issue types to context | [View](../operations/addIssueTypesToContext.md) |
| POST | `/rest/api/3/field/{fieldId}/context/{contextId}/issuetype/remove` | Remove issue types from context | [View](../operations/removeIssueTypesFromContext.md) |
| PUT | `/rest/api/3/field/{fieldId}/context/{contextId}/project` | Assign custom field context to projects | [View](../operations/assignProjectsToCustomFieldContext.md) |
| POST | `/rest/api/3/field/{fieldId}/context/{contextId}/project/remove` | Remove custom field context from projects | [View](../operations/removeCustomFieldContextFromProjects.md) |
