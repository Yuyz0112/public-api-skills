# OrchestrationWarningIneligible

This rule is using a feature that is currently unavailable on the current account plan.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `message` | string | No | A description of the warning and any potential side effects. |
| `rule_id` | string | No | The ID of the rule using the feature. |
| `feature` | string | No | The feature that the current account plan does not have access to.

Example values include:
* `threshold_condition`
* `nested_rules`
* `suspend`
* `automation_actions`
* `cache_variable:automation_actions`
* `cache_variable:annotate`
* `variables`
* `interpolation:annotate`
* `interpolation:extractions`
* `interpolation:incident_custom_field_updates`
* `suppress`
* `incident_custom_field_updates`
* `dynamic_route_to`
* `escalation_policy`
* `aiops_routing_mismatch`
 |
| `feature_type` | string | No | Specifies whether the feature is a part of the rule's conditions, or its actions.

Example values include:
* `conditions`
* `actions`
* `nested_rules`
* `global_orchestrations`
* `aiops_routing`
 |
| `warning_type` | enum: forbidden_feature, invalid_routing | No | The type of warning that is being returned for the rule. |

