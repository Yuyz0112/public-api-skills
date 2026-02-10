# Merge request approvals

Operations related to merge request approvals.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/approval_rules` | Get all merge request approval rules | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidApprovalRules.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/approval_rules` | Create new merge request approval rules | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidApprovalRules.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/approval_rules/{approval_rule_id}` | Get merge request approval rule | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidApprovalRulesApprovalRuleId.md) |
| PUT | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/approval_rules/{approval_rule_id}` | Update merge request approval rule | [View](../operations/putApiV4ProjectsIdMergeRequestsMergeRequestIidApprovalRulesApprovalRuleId.md) |
| DELETE | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/approval_rules/{approval_rule_id}` | Destroy merge request approval rule | [View](../operations/deleteApiV4ProjectsIdMergeRequestsMergeRequestIidApprovalRulesApprovalRuleId.md) |
| GET | `/api/v4/projects/{id}/merge_request_approval_setting` | Get project-level MR approval settings | [View](../operations/getApiV4ProjectsIdMergeRequestApprovalSetting.md) |
| PUT | `/api/v4/projects/{id}/merge_request_approval_setting` | Update existing merge request approval setting | [View](../operations/putApiV4ProjectsIdMergeRequestApprovalSetting.md) |
| GET | `/api/v4/groups/{id}/merge_request_approval_setting` | Get group merge request approval setting | [View](../operations/getApiV4GroupsIdMergeRequestApprovalSetting.md) |
| PUT | `/api/v4/groups/{id}/merge_request_approval_setting` | Update existing merge request approval setting | [View](../operations/putApiV4GroupsIdMergeRequestApprovalSetting.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/approvals` | List approvals for merge request | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidApprovals.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/approvals` | Deprecated in 16.0: Use the merge request approvals API instead. Change approval-related configuration | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidApprovals.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/approve` | Approve a merge request | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidApprove.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/unapprove` | Remove an approval from a merge request | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidUnapprove.md) |
| PUT | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/reset_approvals` | Remove all merge request approvals | [View](../operations/putApiV4ProjectsIdMergeRequestsMergeRequestIidResetApprovals.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/approval_settings` | List approval rules for merge request | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidApprovalSettings.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/approval_state` | Get approval state of merge request | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidApprovalState.md) |
