# pages_deployment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `aliases` | string[] | Yes | A list of alias URLs pointing to this deployment. |
| `build_config` | [pages_build_config](pages-build-config.md) | Yes |  |
| `created_on` | string (date-time) | Yes | When the deployment was created. |
| `deployment_trigger` | object | Yes | Info about what caused the deployment. |
| `env_vars` | [pages_env_vars](pages-env-vars.md) | Yes |  |
| `environment` | enum: preview, production | Yes | Type of deploy. |
| `id` | string | Yes | Id of the deployment. |
| `is_skipped` | boolean | Yes | If the deployment has been skipped. |
| `latest_stage` | [pages_stage](pages-stage.md) | Yes |  |
| `modified_on` | string (date-time) | Yes | When the deployment was last modified. |
| `project_id` | string | Yes | Id of the project. |
| `project_name` | [pages_project_name](pages-project-name.md) | Yes |  |
| `short_id` | string | Yes | Short Id (8 character) of the deployment. |
| `source` | [pages_source](pages-source.md) | Yes |  |
| `stages` | pages_stage[] | Yes | List of past stages. |
| `url` | string | Yes | The live URL to view this deployment. |
| `uses_functions` | boolean | No | Whether the deployment uses functions. |

## Nested Fields

### `deployment_trigger`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `metadata` | object | Yes | Additional info about the trigger. |
| `type` | enum: github:push, ad_hoc, deploy_hook | Yes | What caused the deployment. |

#### `deployment_trigger.metadata`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `branch` | string | Yes | Where the trigger happened. |
| `commit_dirty` | boolean | Yes | Whether the deployment trigger commit was dirty. |
| `commit_hash` | string | Yes | Hash of the deployment trigger commit. |
| `commit_message` | string | Yes | Message of the deployment trigger commit. |

