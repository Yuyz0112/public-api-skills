# environment

Details of a deployment environment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes | The id of the environment. |
| `node_id` | string | Yes |  |
| `name` | string | Yes | The name of the environment. |
| `url` | string | Yes |  |
| `html_url` | string | Yes |  |
| `created_at` | string (date-time) | Yes | The time that the environment was created, in ISO 8601 format. |
| `updated_at` | string (date-time) | Yes | The time that the environment was last updated, in ISO 8601 format. |
| `protection_rules` | any[] | No | Built-in deployment protection rules for the environment. |
| `deployment_branch_policy` | [deployment-branch-policy-settings](deployment-branch-policy-settings.md) | No |  |

