# POST /api/v4/projects/{id}/merge_requests/{merge_request_iid}/approval_rules

**Resource:** [Merge request approvals](../resources/Merge-request-approvals.md)
**Create new merge request approval rules**
**Operation ID:** `postApiV4ProjectsIdMergeRequestsMergeRequestIidApprovalRules`

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

[APIEntitiesMergeRequestApprovalRule](../schemas/APIEntitiesMergeRequestApprovalRule/APIEntitiesMergeRequestApprovalRule.md)

