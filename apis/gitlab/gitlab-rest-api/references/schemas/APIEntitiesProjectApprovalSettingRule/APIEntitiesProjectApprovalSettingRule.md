# APIEntitiesProjectApprovalSettingRule

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
| `protected_branches` | [APIEntitiesProtectedBranch](APIEntitiesProtectedBranch.md) | No |  |
| `applies_to_all_protected_branches` | string | No |  |
| `approvers` | [APIEntitiesUserBasic](APIEntitiesUserBasic.md) | No |  |
| `scanners` | string | No |  |
| `vulnerabilities_allowed` | string | No |  |
| `severity_levels` | string | No |  |
| `vulnerability_states` | string | No |  |

