# Issue type schemes

This resource represents issue type schemes in classic projects. Use it to:

 *  get issue type schemes and a list of the projects that use them.
 *  associate issue type schemes with projects.
 *  add issue types to issue type schemes.
 *  delete issue types from issue type schemes.
 *  create, update, and delete issue type schemes.
 *  change the order of issue types in issue type schemes.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/issuetypescheme` | Get all issue type schemes | [View](../operations/getAllIssueTypeSchemes.md) |
| POST | `/rest/api/3/issuetypescheme` | Create issue type scheme | [View](../operations/createIssueTypeScheme.md) |
| GET | `/rest/api/3/issuetypescheme/mapping` | Get issue type scheme items | [View](../operations/getIssueTypeSchemesMapping.md) |
| GET | `/rest/api/3/issuetypescheme/project` | Get issue type schemes for projects | [View](../operations/getIssueTypeSchemeForProjects.md) |
| PUT | `/rest/api/3/issuetypescheme/project` | Assign issue type scheme to project | [View](../operations/assignIssueTypeSchemeToProject.md) |
| PUT | `/rest/api/3/issuetypescheme/{issueTypeSchemeId}` | Update issue type scheme | [View](../operations/updateIssueTypeScheme.md) |
| DELETE | `/rest/api/3/issuetypescheme/{issueTypeSchemeId}` | Delete issue type scheme | [View](../operations/deleteIssueTypeScheme.md) |
| PUT | `/rest/api/3/issuetypescheme/{issueTypeSchemeId}/issuetype` | Add issue types to issue type scheme | [View](../operations/addIssueTypesToIssueTypeScheme.md) |
| PUT | `/rest/api/3/issuetypescheme/{issueTypeSchemeId}/issuetype/move` | Change order of issue types | [View](../operations/reorderIssueTypesInIssueTypeScheme.md) |
| DELETE | `/rest/api/3/issuetypescheme/{issueTypeSchemeId}/issuetype/{issueTypeId}` | Remove issue type from issue type scheme | [View](../operations/removeIssueTypeFromIssueTypeScheme.md) |
