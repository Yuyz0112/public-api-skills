# PUT /api/v4/projects/{id}/approval_rules/{approval_rule_id}

**Resource:** [Approval rules](../resources/Approval-rules.md)
**Update project approval rule**
**Operation ID:** `putApiV4ProjectsIdApprovalRulesApprovalRuleId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `approval_rule_id` | path | integer | Yes | The ID of an approval_rule |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectApprovalRule](../schemas/APIEntitiesProjectApprovalRule/APIEntitiesProjectApprovalRule.md)

