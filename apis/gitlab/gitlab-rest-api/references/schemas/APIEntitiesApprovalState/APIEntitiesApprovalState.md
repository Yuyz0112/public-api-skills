# APIEntitiesApprovalState

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `merge_request` | [APIEntitiesIssuableEntity](APIEntitiesIssuableEntity.md) | No |  |
| `merge_status` | string | No |  |
| `approved` | Boolean | No |  |
| `approvals_required` | integer | No |  |
| `approvals_left` | integer | No |  |
| `require_password_to_approve` | Boolean | No |  |
| `approved_by` | APIEntitiesApprovals[] | No |  |
| `suggested_approvers` | APIEntitiesUserBasic[] | No |  |
| `approvers` | string | No |  |
| `approver_groups` | string | No |  |
| `user_has_approved` | Boolean | No |  |
| `user_can_approve` | Boolean | No |  |
| `approval_rules_left` | APIEntitiesApprovalRuleShort[] | No |  |
| `has_approval_rules` | Boolean | No |  |
| `merge_request_approvers_available` | Boolean | No |  |
| `multiple_approval_rules_available` | Boolean | No |  |
| `invalid_approvers_rules` | APIEntitiesApprovalRuleShort[] | No |  |

