# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/approval_settings

**Resource:** [Merge request approvals](../resources/Merge-request-approvals.md)
**List approval rules for merge request**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidApprovalSettings`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `merge_request_iid` | path | integer | Yes | The IID of a merge request |
| `target_branch` | query | string | No | Branch that scoped approval rules apply to |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

