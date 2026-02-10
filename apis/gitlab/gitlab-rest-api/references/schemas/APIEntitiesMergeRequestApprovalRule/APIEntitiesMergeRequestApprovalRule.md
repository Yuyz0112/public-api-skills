# APIEntitiesMergeRequestApprovalRule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `name` | string | No |  |
| `rule_type` | string | No |  |
| `eligible_approvers` | APIEntitiesUserBasic[] | No |  |
| `approvals_required` | integer | No |  |
| `users` | APIEntitiesUserBasic[] | No |  |
| `groups` | APIEntitiesGroup[] | No |  |
| `contains_hidden_groups` | Boolean | No |  |
| `report_type` | string | No |  |
| `section` | string | No |  |
| `source_rule` | [APIEntitiesMergeRequestApprovalRuleSourceRule](APIEntitiesMergeRequestApprovalRuleSourceRule.md) | No |  |
| `overridden` | Boolean | No |  |

