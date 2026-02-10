# GET /api/v4/projects/{id}/merge_request_approval_setting

**Resource:** [Merge request approvals](../resources/Merge-request-approvals.md)
**Get project-level MR approval settings**
**Operation ID:** `getApiV4ProjectsIdMergeRequestApprovalSetting`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |

**Success Response Schema:**

[APIEntitiesMergeRequestApprovalSetting](../schemas/APIEntitiesMergeRequestApprovalSetting/APIEntitiesMergeRequestApprovalSetting.md)

