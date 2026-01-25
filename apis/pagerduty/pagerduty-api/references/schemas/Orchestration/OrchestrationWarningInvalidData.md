# OrchestrationWarningInvalidData

This rule includes invalid data for a feature item.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | No | A description of the warning and any potential side effects. |
| `rule_id` | string | No | The ID of the rule using the feature. |
| `feature` | string | No | The feature that includes invalid data.

Example values include:
  * `incident_custom_field_updates`
  * `escalation_policy`
  * `cache_variable:annotate`
  * `cache_variable:conditions`
  * `cache_variable:automation_actions`
 |
| `feature_type` | string | No | Specifies the feature type of the impacted item.

Example values include:
  * `actions`
  * `conditions`
 |
| `warning_type` | enum: invalid_data | No | The type of warning that is being returned for the rule. |

