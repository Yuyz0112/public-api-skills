# PUT /api/v4/groups/{id}/merge_request_approval_setting

**Resource:** [Merge request approvals](../resources/Merge-request-approvals.md)
**Update existing merge request approval setting**
**Operation ID:** `putApiV4GroupsIdMergeRequestApprovalSetting`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of a group |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Validation error |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesMergeRequestApprovalSetting](../schemas/APIEntitiesMergeRequestApprovalSetting/APIEntitiesMergeRequestApprovalSetting.md)

