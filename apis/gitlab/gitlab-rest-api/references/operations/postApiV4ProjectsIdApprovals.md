# POST /api/v4/projects/{id}/approvals

**Resource:** [Project approvals](../resources/Project-approvals.md)
**Change approval-related configuration**
**Operation ID:** `postApiV4ProjectsIdApprovals`

This feature was introduced in 10.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesApprovalSettings](../schemas/APIEntitiesApprovalSettings/APIEntitiesApprovalSettings.md)

