# RuleConfiguration

A rule configuration.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `disabled` | boolean | No | Whether the rule is disabled. |
| `tag` | string | No | A tag used to filter rules in [Get workflow transition rule configurations](https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflow-transition-rules/#api-rest-api-3-workflow-rule-config-get). |
| `value` | string | Yes | Configuration of the rule, as it is stored by the Connect or the Forge app on the rule configuration page. |

