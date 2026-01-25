# Issue type screen schemes

This resource represents issue type screen schemes. Use it to:

 *  get issue type screen schemes and a list of the projects that use them.
 *  create issue type screen schemes.
 *  update issue type screen schemes.
 *  delete issue type screen schemes.
 *  associate issue type screen schemes with projects.
 *  append issue type to screen scheme mappings to issue type screen schemes.
 *  remove issue type to screen scheme mappings from issue type screen schemes.
 *  update default screen scheme of issue type screen scheme.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/issuetypescreenscheme` | Get issue type screen schemes | [View](../operations/getIssueTypeScreenSchemes.md) |
| POST | `/rest/api/3/issuetypescreenscheme` | Create issue type screen scheme | [View](../operations/createIssueTypeScreenScheme.md) |
| GET | `/rest/api/3/issuetypescreenscheme/mapping` | Get issue type screen scheme items | [View](../operations/getIssueTypeScreenSchemeMappings.md) |
| GET | `/rest/api/3/issuetypescreenscheme/project` | Get issue type screen schemes for projects | [View](../operations/getIssueTypeScreenSchemeProjectAssociations.md) |
| PUT | `/rest/api/3/issuetypescreenscheme/project` | Assign issue type screen scheme to project | [View](../operations/assignIssueTypeScreenSchemeToProject.md) |
| PUT | `/rest/api/3/issuetypescreenscheme/{issueTypeScreenSchemeId}` | Update issue type screen scheme | [View](../operations/updateIssueTypeScreenScheme.md) |
| DELETE | `/rest/api/3/issuetypescreenscheme/{issueTypeScreenSchemeId}` | Delete issue type screen scheme | [View](../operations/deleteIssueTypeScreenScheme.md) |
| PUT | `/rest/api/3/issuetypescreenscheme/{issueTypeScreenSchemeId}/mapping` | Append mappings to issue type screen scheme | [View](../operations/appendMappingsForIssueTypeScreenScheme.md) |
| PUT | `/rest/api/3/issuetypescreenscheme/{issueTypeScreenSchemeId}/mapping/default` | Update issue type screen scheme default screen scheme | [View](../operations/updateDefaultScreenScheme.md) |
| POST | `/rest/api/3/issuetypescreenscheme/{issueTypeScreenSchemeId}/mapping/remove` | Remove mappings from issue type screen scheme | [View](../operations/removeMappingsFromIssueTypeScreenScheme.md) |
| GET | `/rest/api/3/issuetypescreenscheme/{issueTypeScreenSchemeId}/project` | Get issue type screen scheme projects | [View](../operations/getProjectsForIssueTypeScreenScheme.md) |
