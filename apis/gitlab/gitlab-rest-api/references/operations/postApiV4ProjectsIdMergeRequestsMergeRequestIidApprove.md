# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/approve

**Resource:** [Merge request approvals](../resources/Merge-request-approvals.md)
**Approve a merge request**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidApprove`

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesMergeRequestApprovals](../schemas/APIEntitiesMergeRequestApprovals/APIEntitiesMergeRequestApprovals.md)

