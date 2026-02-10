# GET /api/v4/projects/{id}/merge_requests/{merge_request_iid}/approval_rules/{approval_rule_id}

**Resource:** [Merge request approvals](../resources/Merge-request-approvals.md)
**Get merge request approval rule**
**Operation ID:** `getApiV4ProjectsIdMergeRequestsMergeRequestIidApprovalRulesApprovalRuleId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `merge_request_iid` | path | integer | Yes | The IID of a merge request |
| `approval_rule_id` | path | integer | Yes | The ID of a merge request approval rule |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMergeRequestApprovalRule](../schemas/APIEntitiesMergeRequestApprovalRule/APIEntitiesMergeRequestApprovalRule.md)

