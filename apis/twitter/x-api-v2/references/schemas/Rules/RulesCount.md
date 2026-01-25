# RulesCount

A count of user-provided stream filtering rules at the application and project levels.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `all_project_client_apps` | [AllProjectClientApps](AllProjectClientApps.md) | No |  |
| `cap_per_client_app` | integer (int32) | No | Cap of number of rules allowed per client application |
| `cap_per_project` | integer (int32) | No | Cap of number of rules allowed per project |
| `client_app_rules_count` | [AppRulesCount](AppRulesCount.md) | No |  |
| `project_rules_count` | integer (int32) | No | Number of rules for project |

