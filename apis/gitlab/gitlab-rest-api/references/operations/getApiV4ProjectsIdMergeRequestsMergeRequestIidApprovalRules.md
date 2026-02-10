# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/approval_rules

**Resource:** [Merge request approvals](../resources/Merge-request-approvals.md)
**Get all merge request approval rules**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidApprovalRules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `merge_request_iid` | path | integer | Yes | The IID of a merge request |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMergeRequestApprovalRule](../schemas/APIEntitiesMergeRequestApprovalRule/APIEntitiesMergeRequestApprovalRule.md)

