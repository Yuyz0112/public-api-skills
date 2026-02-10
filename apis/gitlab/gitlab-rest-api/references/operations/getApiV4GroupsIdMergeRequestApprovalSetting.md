# GET /api/v4/groups/{id}/merge_request_approval_setting

**Resource:** [Merge request approvals](../resources/Merge-request-approvals.md)
**Get group merge request approval setting**
**Operation ID:** `getApiV4GroupsIdMergeRequestApprovalSetting`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of a group |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesMergeRequestApprovalSetting](../schemas/APIEntitiesMergeRequestApprovalSetting/APIEntitiesMergeRequestApprovalSetting.md)

