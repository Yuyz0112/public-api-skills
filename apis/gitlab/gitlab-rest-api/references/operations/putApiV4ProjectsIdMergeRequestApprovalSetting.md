# PUT /api/v4/projects/{id}/merge_request_approval_setting

**Resource:** [Merge request approvals](../resources/Merge-request-approvals.md)
**Update existing merge request approval setting**
**Operation ID:** `putApiV4ProjectsIdMergeRequestApprovalSetting`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

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

