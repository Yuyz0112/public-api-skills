# GET /api/v4/projects/{id}/approval_rules/{approval_rule_id}

**Resource:** [Approval rules](../resources/Approval-rules.md)
**Get a single approval rule**
**Operation ID:** `getApiV4ProjectsIdApprovalRulesApprovalRuleId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectApprovalRule](../schemas/APIEntitiesProjectApprovalRule/APIEntitiesProjectApprovalRule.md)

