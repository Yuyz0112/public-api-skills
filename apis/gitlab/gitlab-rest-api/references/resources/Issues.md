# Issues

Operations related to issues.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/issues_statistics` | Get currently authenticated user's issues statistics | [View](../operations/getApiV4IssuesStatistics.md) |
| GET | `/api/v4/issues` | Get currently authenticated user's issues | [View](../operations/getApiV4Issues.md) |
| GET | `/api/v4/issues/{id}` | Get specified issue (admin only) | [View](../operations/getApiV4IssuesId.md) |
| POST | `/api/v4/projects/{id}/issues/{issue_iid}/time_estimate` | Set a time estimate for a issue | [View](../operations/postApiV4ProjectsIdIssuesIssueIidTimeEstimate.md) |
| POST | `/api/v4/projects/{id}/issues/{issue_iid}/reset_time_estimate` | Reset the time estimate for a project issue | [View](../operations/postApiV4ProjectsIdIssuesIssueIidResetTimeEstimate.md) |
| POST | `/api/v4/projects/{id}/issues/{issue_iid}/add_spent_time` | Add spent time for a issue | [View](../operations/postApiV4ProjectsIdIssuesIssueIidAddSpentTime.md) |
| POST | `/api/v4/projects/{id}/issues/{issue_iid}/reset_spent_time` | Reset spent time for a issue | [View](../operations/postApiV4ProjectsIdIssuesIssueIidResetSpentTime.md) |
| GET | `/api/v4/projects/{id}/issues/{issue_iid}/time_stats` | Get time tracking stats | [View](../operations/getApiV4ProjectsIdIssuesIssueIidTimeStats.md) |
| GET | `/api/v4/projects/{id}/issues/{issue_iid}/related_merge_requests` | List merge requests that are related to the issue | [View](../operations/getApiV4ProjectsIdIssuesIssueIidRelatedMergeRequests.md) |
| GET | `/api/v4/projects/{id}/issues/{issue_iid}/participants` | List participants for an issue | [View](../operations/getApiV4ProjectsIdIssuesIssueIidParticipants.md) |
| GET | `/api/v4/projects/{id}/issues/{issue_iid}/user_agent_detail` | Get the user agent details for an issue | [View](../operations/getApiV4ProjectsIdIssuesIssueIidUserAgentDetail.md) |
| GET | `/api/v4/projects/{id}/issues/{issue_iid}/links` | List issue relations | [View](../operations/getApiV4ProjectsIdIssuesIssueIidLinks.md) |
| POST | `/api/v4/projects/{id}/issues/{issue_iid}/links` | Create an issue link | [View](../operations/postApiV4ProjectsIdIssuesIssueIidLinks.md) |
| GET | `/api/v4/projects/{id}/issues/{issue_iid}/links/{issue_link_id}` | Get an issue link | [View](../operations/getApiV4ProjectsIdIssuesIssueIidLinksIssueLinkId.md) |
| DELETE | `/api/v4/projects/{id}/issues/{issue_iid}/links/{issue_link_id}` | Delete an issue link | [View](../operations/deleteApiV4ProjectsIdIssuesIssueIidLinksIssueLinkId.md) |
