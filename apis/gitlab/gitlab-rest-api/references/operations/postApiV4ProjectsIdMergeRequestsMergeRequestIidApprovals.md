# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/approvals

**Resource:** [Merge request approvals](../resources/Merge-request-approvals.md)
**Deprecated in 16.0: Use the merge request approvals API instead. Change approval-related configuration**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidApprovals`
⚠️ **Deprecated**

This feature was introduced in 10.6 and deprecated in 16.0

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `merge_request_iid` | path | integer | Yes | The IID of a merge request |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesApprovalState](../schemas/APIEntitiesApprovalState/APIEntitiesApprovalState.md)

