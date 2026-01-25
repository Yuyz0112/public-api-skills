# Issue security schemes

This resource represents issue security schemes. Use it to get an issue security scheme or a list of issue security schemes.

Issue security schemes control which users or groups of users can view an issue. When an issue security scheme is associated with a project, its security levels can be applied to issues in that project. Sub-tasks also inherit the security level of their parent issue.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/issuesecurityschemes` | Get issue security schemes | [View](../operations/getIssueSecuritySchemes.md) |
| POST | `/rest/api/3/issuesecurityschemes` | Create issue security scheme | [View](../operations/createIssueSecurityScheme.md) |
| GET | `/rest/api/3/issuesecurityschemes/level` | Get issue security levels | [View](../operations/getSecurityLevels.md) |
| PUT | `/rest/api/3/issuesecurityschemes/level/default` | Set default issue security levels | [View](../operations/setDefaultLevels.md) |
| GET | `/rest/api/3/issuesecurityschemes/level/member` | Get issue security level members | [View](../operations/getSecurityLevelMembers.md) |
| GET | `/rest/api/3/issuesecurityschemes/project` | Get projects using issue security schemes | [View](../operations/searchProjectsUsingSecuritySchemes.md) |
| PUT | `/rest/api/3/issuesecurityschemes/project` | Associate security scheme to project | [View](../operations/associateSchemesToProjects.md) |
| GET | `/rest/api/3/issuesecurityschemes/search` | Search issue security schemes | [View](../operations/searchSecuritySchemes.md) |
| GET | `/rest/api/3/issuesecurityschemes/{id}` | Get issue security scheme | [View](../operations/getIssueSecurityScheme.md) |
| PUT | `/rest/api/3/issuesecurityschemes/{id}` | Update issue security scheme | [View](../operations/updateIssueSecurityScheme.md) |
| DELETE | `/rest/api/3/issuesecurityschemes/{schemeId}` | Delete issue security scheme | [View](../operations/deleteSecurityScheme.md) |
| PUT | `/rest/api/3/issuesecurityschemes/{schemeId}/level` | Add issue security levels | [View](../operations/addSecurityLevel.md) |
| PUT | `/rest/api/3/issuesecurityschemes/{schemeId}/level/{levelId}` | Update issue security level | [View](../operations/updateSecurityLevel.md) |
| DELETE | `/rest/api/3/issuesecurityschemes/{schemeId}/level/{levelId}` | Remove issue security level | [View](../operations/removeLevel.md) |
| PUT | `/rest/api/3/issuesecurityschemes/{schemeId}/level/{levelId}/member` | Add issue security level members | [View](../operations/addSecurityLevelMembers.md) |
| DELETE | `/rest/api/3/issuesecurityschemes/{schemeId}/level/{levelId}/member/{memberId}` | Remove member from issue security level | [View](../operations/removeMemberFromSecurityLevel.md) |
