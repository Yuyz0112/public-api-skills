# GET /api/v4/projects/{id}/approvals

**Resource:** [Project approvals](../resources/Project-approvals.md)
**Get all project approvers and related configuration**
**Operation ID:** `getApiV4ProjectsIdApprovals`

This feature was introduced in 10.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesApprovalSettings](../schemas/APIEntitiesApprovalSettings/APIEntitiesApprovalSettings.md)

