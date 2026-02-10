# External status checks

Operations related to external status checks.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/external_status_checks` | Get project external status checks | [View](../operations/getApiV4ProjectsIdExternalStatusChecks.md) |
| POST | `/api/v4/projects/{id}/external_status_checks` | Create external status check | [View](../operations/postApiV4ProjectsIdExternalStatusChecks.md) |
| PUT | `/api/v4/projects/{id}/external_status_checks/{check_id}` | Update external status check | [View](../operations/putApiV4ProjectsIdExternalStatusChecksCheckId.md) |
| DELETE | `/api/v4/projects/{id}/external_status_checks/{check_id}` | Delete external status check | [View](../operations/deleteApiV4ProjectsIdExternalStatusChecksCheckId.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/status_check_responses` | Set status of an external status check | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidStatusCheckResponses.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/status_checks` | List status checks for a merge request | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidStatusChecks.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/status_checks/{external_status_check_id}/retry` | Retry failed external status check | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidStatusChecksExternalStatusCheckIdRetry.md) |
