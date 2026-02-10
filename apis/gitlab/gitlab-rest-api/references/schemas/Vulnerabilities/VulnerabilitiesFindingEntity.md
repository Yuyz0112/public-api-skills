# VulnerabilitiesFindingEntity

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | string | No |  |
| `report_type` | string | No |  |
| `name` | string | No |  |
| `severity` | string | No |  |
| `scanner` | [VulnerabilitiesScannerEntity](VulnerabilitiesScannerEntity.md) | No |  |
| `identifiers` | [VulnerabilitiesIdentifierEntity](VulnerabilitiesIdentifierEntity.md) | No |  |
| `uuid` | string | No |  |
| `create_jira_issue_url` | string | No |  |
| `false_positive` | string | No |  |
| `create_vulnerability_feedback_issue_path` | string | No |  |
| `create_vulnerability_feedback_merge_request_path` | string | No |  |
| `create_vulnerability_feedback_dismissal_path` | string | No |  |
| `project` | [ProjectEntity](ProjectEntity.md) | No |  |
| `dismissal_feedback` | [VulnerabilitiesFeedbackEntity](VulnerabilitiesFeedbackEntity.md) | No |  |
| `issue_feedback` | [VulnerabilitiesFeedbackEntity](VulnerabilitiesFeedbackEntity.md) | No |  |
| `merge_request_feedback` | [VulnerabilitiesFeedbackEntity](VulnerabilitiesFeedbackEntity.md) | No |  |
| `state_transitions` | [VulnerabilitiesStateTransitionEntity](VulnerabilitiesStateTransitionEntity.md) | No |  |
| `issue_links` | [VulnerabilitiesIssueLinkEntity](VulnerabilitiesIssueLinkEntity.md) | No |  |
| `external_issue_links` | [VulnerabilitiesExternalIssueLinkEntity](VulnerabilitiesExternalIssueLinkEntity.md) | No |  |
| `merge_request_links` | [VulnerabilitiesMergeRequestLinkEntity](VulnerabilitiesMergeRequestLinkEntity.md) | No |  |
| `metadata` | string | No |  |
| `details` | string | No |  |
| `state` | string | No |  |
| `scan` | string | No |  |
| `blob_path` | string | No |  |
| `found_by_pipeline` | string | No |  |
| `ai_resolution_enabled` | string | No |  |
| `matches_auto_dismiss_policy` | string | No |  |

