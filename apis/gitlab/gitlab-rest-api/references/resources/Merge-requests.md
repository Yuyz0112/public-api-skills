# Merge requests

Operations related to merge requests.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/blocks` | Get all merge request dependencies | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidBlocks.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/blockees` | Get all merge requests are blockees for this merge request | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidBlockees.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/versions` | Get a list of merge request diff versions | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidVersions.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/versions/{version_id}` | Get a single merge request diff version | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidVersionsVersionId.md) |
| GET | `/api/v4/merge_requests` | List merge requests | [View](../operations/getApiV4MergeRequests.md) |
| GET | `/api/v4/groups/{id}/merge_requests` | List group merge requests | [View](../operations/getApiV4GroupsIdMergeRequests.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/time_estimate` | Set a time estimate for a merge_request | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidTimeEstimate.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/reset_time_estimate` | Reset the time estimate for a project merge_request | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidResetTimeEstimate.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/add_spent_time` | Add spent time for a merge_request | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidAddSpentTime.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/reset_spent_time` | Reset spent time for a merge_request | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidResetSpentTime.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/time_stats` | Get time tracking stats | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidTimeStats.md) |
| GET | `/api/v4/projects/{id}/merge_requests` | List project merge requests | [View](../operations/getApiV4ProjectsIdMergeRequests.md) |
| POST | `/api/v4/projects/{id}/merge_requests` | Create merge request | [View](../operations/postApiV4ProjectsIdMergeRequests.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}` | Get single merge request | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIid.md) |
| PUT | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}` | Update merge request | [View](../operations/putApiV4ProjectsIdMergeRequestsMergeRequestIid.md) |
| DELETE | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}` | Delete a merge request | [View](../operations/deleteApiV4ProjectsIdMergeRequestsMergeRequestIid.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/participants` | Get single merge request participants | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidParticipants.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/reviewers` | Get single merge request reviewers | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidReviewers.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/commits` | Get single merge request commits | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidCommits.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/context_commits` | List merge request context commits | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidContextCommits.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/context_commits` | Create merge request context commits | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidContextCommits.md) |
| DELETE | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/context_commits` | Delete merge request context commits | [View](../operations/deleteApiV4ProjectsIdMergeRequestsMergeRequestIidContextCommits.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/changes` | Get single merge request changes | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidChanges.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/diffs` | Get the merge request diffs | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidDiffs.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/raw_diffs` | Get the merge request raw diffs | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidRawDiffs.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/pipelines` | Get single merge request pipelines | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidPipelines.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/pipelines` | Create merge request pipeline | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidPipelines.md) |
| PUT | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/merge` | Merge a merge request | [View](../operations/putApiV4ProjectsIdMergeRequestsMergeRequestIidMerge.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/merge_ref` | Returns the up to date merge-ref HEAD commit | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidMergeRef.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/cancel_merge_when_pipeline_succeeds` | Cancel Merge When Pipeline Succeeds | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidCancelMergeWhenPipelineSucceeds.md) |
| PUT | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/rebase` | Rebase a merge request | [View](../operations/putApiV4ProjectsIdMergeRequestsMergeRequestIidRebase.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/closes_issues` | List issues that close on merge | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidClosesIssues.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/related_issues` | List issues related to merge request | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidRelatedIssues.md) |
