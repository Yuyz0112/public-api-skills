# GET /api/v4/projects/{id}/approval_settings

**Resource:** [Approval rules](../resources/Approval-rules.md)
**Get all project approval rules**
**Operation ID:** `getApiV4ProjectsIdApprovalSettings`

Private API subject to change

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `target_branch` | query | string | No | Branch that scoped approval rules apply to |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectApprovalSettings](../schemas/APIEntitiesProjectApprovalSettings/APIEntitiesProjectApprovalSettings.md)

