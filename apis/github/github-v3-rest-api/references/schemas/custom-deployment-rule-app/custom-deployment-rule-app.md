# custom-deployment-rule-app

A GitHub App that is providing a custom deployment protection rule.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The unique identifier of the deployment protection rule integration. |
| `slug` | string | Yes | The slugified name of the deployment protection rule integration. |
| `integration_url` | string | Yes | The URL for the endpoint to get details about the app. |
| `node_id` | string | Yes | The node ID for the deployment protection rule integration. |

