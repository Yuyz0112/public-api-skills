# deployment-status

The status of a deployment.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `id` | integer (int64) | Yes |  |
| `node_id` | string | Yes |  |
| `state` | enum: error, failure, inactive... | Yes | The state of the status. |
| `creator` | [nullable-simple-user](nullable-simple-user.md) | Yes |  |
| `description` | string | Yes | A short description of the status. |
| `environment` | string | No | The environment of the deployment that the status is for. |
| `target_url` | string (uri) | Yes | Closing down notice: the URL to associate with this status. |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `deployment_url` | string (uri) | Yes |  |
| `repository_url` | string (uri) | Yes |  |
| `environment_url` | string (uri) | No | The URL for accessing your environment. |
| `log_url` | string (uri) | No | The URL to associate with this status. |
| `performed_via_github_app` | [nullable-integration](nullable-integration.md) | No |  |

