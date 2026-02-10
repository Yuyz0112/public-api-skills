# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/approval_state

**Resource:** [Merge request approvals](../resources/Merge-request-approvals.md)
**Get approval state of merge request**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidApprovalState`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `merge_request_iid` | path | integer | Yes | The IID of a merge request |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMergeRequestApprovalState](../schemas/APIEntitiesMergeRequestApprovalState/APIEntitiesMergeRequestApprovalState.md)

