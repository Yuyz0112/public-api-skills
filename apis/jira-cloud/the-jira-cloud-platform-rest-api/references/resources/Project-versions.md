# Project versions

This resource represents project versions. Use it to get, get lists of, create, update, move, merge, and delete project versions. This resource also provides counts of issues by version.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/project/{projectIdOrKey}/version` | Get project versions paginated | [View](../operations/getProjectVersionsPaginated.md) |
| GET | `/rest/api/3/project/{projectIdOrKey}/versions` | Get project versions | [View](../operations/getProjectVersions.md) |
| POST | `/rest/api/3/version` | Create version | [View](../operations/createVersion.md) |
| GET | `/rest/api/3/version/{id}` | Get version | [View](../operations/getVersion.md) |
| PUT | `/rest/api/3/version/{id}` | Update version | [View](../operations/updateVersion.md) |
| DELETE | `/rest/api/3/version/{id}` | Delete version | [View](../operations/deleteVersion.md) |
| PUT | `/rest/api/3/version/{id}/mergeto/{moveIssuesTo}` | Merge versions | [View](../operations/mergeVersions.md) |
| POST | `/rest/api/3/version/{id}/move` | Move version | [View](../operations/moveVersion.md) |
| GET | `/rest/api/3/version/{id}/relatedIssueCounts` | Get version's related issues count | [View](../operations/getVersionRelatedIssues.md) |
| GET | `/rest/api/3/version/{id}/relatedwork` | Get related work | [View](../operations/getRelatedWork.md) |
| PUT | `/rest/api/3/version/{id}/relatedwork` | Update related work | [View](../operations/updateRelatedWork.md) |
| POST | `/rest/api/3/version/{id}/relatedwork` | Create related work | [View](../operations/createRelatedWork.md) |
| POST | `/rest/api/3/version/{id}/removeAndSwap` | Delete and replace version | [View](../operations/deleteAndReplaceVersion.md) |
| GET | `/rest/api/3/version/{id}/unresolvedIssueCount` | Get version's unresolved issues count | [View](../operations/getVersionUnresolvedIssues.md) |
| DELETE | `/rest/api/3/version/{versionId}/relatedwork/{relatedWorkId}` | Delete related work | [View](../operations/deleteRelatedWork.md) |
