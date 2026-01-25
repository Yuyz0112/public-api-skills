# Issue remote links

This resource represents remote issue links, a way of linking Jira to information in other systems. Use it to get, create, update, and delete remote issue links either by ID or global ID. The global ID provides a way of accessing remote issue links using information about the item's remote system host and remote system identifier.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/issue/{issueIdOrKey}/remotelink` | Get remote issue links | [View](../operations/getRemoteIssueLinks.md) |
| POST | `/rest/api/3/issue/{issueIdOrKey}/remotelink` | Create or update remote issue link | [View](../operations/createOrUpdateRemoteIssueLink.md) |
| DELETE | `/rest/api/3/issue/{issueIdOrKey}/remotelink` | Delete remote issue link by global ID | [View](../operations/deleteRemoteIssueLinkByGlobalId.md) |
| GET | `/rest/api/3/issue/{issueIdOrKey}/remotelink/{linkId}` | Get remote issue link by ID | [View](../operations/getRemoteIssueLinkById.md) |
| PUT | `/rest/api/3/issue/{issueIdOrKey}/remotelink/{linkId}` | Update remote issue link by ID | [View](../operations/updateRemoteIssueLink.md) |
| DELETE | `/rest/api/3/issue/{issueIdOrKey}/remotelink/{linkId}` | Delete remote issue link by ID | [View](../operations/deleteRemoteIssueLinkById.md) |
