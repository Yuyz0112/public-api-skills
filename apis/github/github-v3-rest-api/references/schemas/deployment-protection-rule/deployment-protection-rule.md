# deployment-protection-rule

Deployment protection rule

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The unique identifier for the deployment protection rule. |
| `node_id` | string | Yes | The node ID for the deployment protection rule. |
| `enabled` | boolean | Yes | Whether the deployment protection rule is enabled for the environment. |
| `app` | [custom-deployment-rule-app](custom-deployment-rule-app.md) | Yes |  |

