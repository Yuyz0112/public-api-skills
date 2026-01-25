# pages_source

Configs for the project source control.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `config` | object | Yes |  |
| `type` | enum: github, gitlab | Yes | The source control management provider. |

## Nested Fields

### `config`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `deployments_enabled` | boolean | Yes | Whether to enable automatic deployments when pushing to the source repository.
When disabled, no deployments (production or preview) will be triggered automatically.
 |
| `owner` | string | Yes | The owner of the repository. |
| `owner_id` | string | Yes | The owner ID of the repository. |
| `path_excludes` | string[] | Yes | A list of paths that should be excluded from triggering a preview deployment. Wildcard syntax (`*`) is supported. |
| `path_includes` | string[] | Yes | A list of paths that should be watched to trigger a preview deployment. Wildcard syntax (`*`) is supported. |
| `pr_comments_enabled` | boolean | Yes | Whether to enable PR comments. |
| `preview_branch_excludes` | string[] | Yes | A list of branches that should not trigger a preview deployment. Wildcard syntax (`*`) is supported. Must be used with `preview_deployment_setting` set to `custom`. |
| `preview_branch_includes` | string[] | Yes | A list of branches that should trigger a preview deployment. Wildcard syntax (`*`) is supported. Must be used with `preview_deployment_setting` set to `custom`. |
| `preview_deployment_setting` | enum: all, none, custom | Yes | Controls whether commits to preview branches trigger a preview deployment. |
| `production_branch` | string | Yes | The production branch of the repository. |
| `production_deployments_enabled` | boolean | Yes | Whether to trigger a production deployment on commits to the production branch. |
| `repo_id` | string | Yes | The ID of the repository. |
| `repo_name` | string | Yes | The name of the repository. |

