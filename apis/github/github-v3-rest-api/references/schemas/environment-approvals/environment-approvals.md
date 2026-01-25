# environment-approvals

An entry in the reviews log for environment deployments

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `environments` | object[] | Yes | The list of environments that were approved or rejected |
| `state` | enum: approved, rejected, pending | Yes | Whether deployment to the environment(s) was approved or rejected or pending (with comments) |
| `user` | [simple-user](simple-user.md) | Yes |  |
| `comment` | string | Yes | The comment submitted with the deployment review |

## Nested Fields

### `environments`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | No | The id of the environment. |
| `node_id` | string | No |  |
| `name` | string | No | The name of the environment. |
| `url` | string | No |  |
| `html_url` | string | No |  |
| `created_at` | string (date-time) | No | The time that the environment was created, in ISO 8601 format. |
| `updated_at` | string (date-time) | No | The time that the environment was last updated, in ISO 8601 format. |

