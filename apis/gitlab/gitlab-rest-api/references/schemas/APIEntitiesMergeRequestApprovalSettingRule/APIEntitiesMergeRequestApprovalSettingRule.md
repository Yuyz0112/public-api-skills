# APIEntitiesMergeRequestApprovalSettingRule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No |  |
| `name` | string | No |  |
| `rule_type` | string | No |  |
| `approvals_required` | integer | No |  |
| `users` | APIEntitiesUserBasic[] | No |  |
| `groups` | APIEntitiesGroup[] | No |  |
| `contains_hidden_groups` | Boolean | No |  |
| `report_type` | string | No |  |
| `section` | string | No |  |
| `source_rule` | [APIEntitiesMergeRequestApprovalRuleSourceRule](APIEntitiesMergeRequestApprovalRuleSourceRule.md) | No |  |
| `overridden` | Boolean | No |  |
| `code_owner` | Boolean | No |  |
| `approved_by` | APIEntitiesUserBasic[] | No |  |
| `approved` | Boolean | No |  |
| `approvers` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `commented_by` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |

