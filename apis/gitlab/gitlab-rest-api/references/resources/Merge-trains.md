# Merge trains

Operations related to merge trains.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/merge_trains` | Get all merge trains of a project | [View](../operations/getApiV4ProjectsIdMergeTrains.md) |
| GET | `/api/v4/projects/{id}/merge_trains/{target_branch}` | Get the merge train for a project target branch | [View](../operations/getApiV4ProjectsIdMergeTrainsTargetBranch.md) |
| GET | `/api/v4/projects/{id}/merge_trains/merge_requests/{merge_request_iid}` | Get the status of a merge request on a merge train | [View](../operations/getApiV4ProjectsIdMergeTrainsMergeRequestsMergeRequestIid.md) |
| POST | `/api/v4/projects/{id}/merge_trains/merge_requests/{merge_request_iid}` | Add a merge request to a merge train | [View](../operations/postApiV4ProjectsIdMergeTrainsMergeRequestsMergeRequestIid.md) |
