# Issue types

This resource represents issues types. Use it to:

 *  get, create, update, and delete issue types.
 *  get all issue types for a user.
 *  get alternative issue types.
 *  set an avatar for an issue type.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/issuetype` | Get all issue types for user | [View](../operations/getIssueAllTypes.md) |
| POST | `/rest/api/3/issuetype` | Create issue type | [View](../operations/createIssueType.md) |
| GET | `/rest/api/3/issuetype/project` | Get issue types for project | [View](../operations/getIssueTypesForProject.md) |
| GET | `/rest/api/3/issuetype/{id}` | Get issue type | [View](../operations/getIssueType.md) |
| PUT | `/rest/api/3/issuetype/{id}` | Update issue type | [View](../operations/updateIssueType.md) |
| DELETE | `/rest/api/3/issuetype/{id}` | Delete issue type | [View](../operations/deleteIssueType.md) |
| GET | `/rest/api/3/issuetype/{id}/alternatives` | Get alternative issue types | [View](../operations/getAlternativeIssueTypes.md) |
| POST | `/rest/api/3/issuetype/{id}/avatar2` | Load issue type avatar | [View](../operations/createIssueTypeAvatar.md) |
