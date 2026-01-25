# deployment-simple

A deployment created as the result of an Actions check run from a workflow that references an environment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `url` | string (uri) | Yes |  |
| `id` | integer | Yes | Unique identifier of the deployment |
| `node_id` | string | Yes |  |
| `task` | string | Yes | Parameter to specify a task to execute |
| `original_environment` | string | No |  |
| `environment` | string | Yes | Name for the target deployment environment. |
| `description` | string | Yes |  |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `statuses_url` | string (uri) | Yes |  |
| `repository_url` | string (uri) | Yes |  |
| `transient_environment` | boolean | No | Specifies if the given environment is will no longer exist at some point in the future. Default: false. |
| `production_environment` | boolean | No | Specifies if the given environment is one that end-users directly interact with. Default: false. |
| `performed_via_github_app` | [nullable-integration](nullable-integration.md) | No |  |

