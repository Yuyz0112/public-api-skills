# PUT /api/v4/groups/{id}/approval_rules/{approval_rule_id}

**Resource:** [Approval rules](../resources/Approval-rules.md)
**Update group approval rule**
**Operation ID:** `putApiV4GroupsIdApprovalRulesApprovalRuleId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesGroupApprovalRule](../schemas/APIEntitiesGroupApprovalRule/APIEntitiesGroupApprovalRule.md)

