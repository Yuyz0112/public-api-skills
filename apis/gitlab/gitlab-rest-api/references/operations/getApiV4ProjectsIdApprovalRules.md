# GET /api/v4/projects/{id}/approval_rules

**Resource:** [Approval rules](../resources/Approval-rules.md)
**Get all project approval rules**
**Operation ID:** `getApiV4ProjectsIdApprovalRules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectApprovalRule](../schemas/APIEntitiesProjectApprovalRule/APIEntitiesProjectApprovalRule.md)

