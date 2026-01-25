# pages_project

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `build_config` | [pages_build_config](pages-build-config.md) | No |  |
| `canonical_deployment` | any | Yes |  |
| `created_on` | string (date-time) | Yes | When the project was created. |
| `deployment_configs` | object | Yes | Configs for deployments in a project. |
| `domains` | string[] | No | A list of associated custom domains for the project. |
| `framework` | string | Yes | Framework the project is using. |
| `framework_version` | string | Yes | Version of the framework the project is using. |
| `id` | string | Yes | ID of the project. |
| `latest_deployment` | any | Yes |  |
| `name` | [pages_project_name](pages-project-name.md) | Yes |  |
| `preview_script_name` | string | Yes | Name of the preview script. |
| `production_branch` | string | Yes | Production branch of the project. Used to identify production deployments. |
| `production_script_name` | string | Yes | Name of the production script. |
| `source` | [pages_source](pages-source.md) | No |  |
| `subdomain` | string | No | The Cloudflare subdomain associated with the project. |
| `uses_functions` | boolean | Yes | Whether the project uses functions. |

## Nested Fields

### `deployment_configs`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `preview` | any | Yes | Configs for preview deploys. |
| `production` | any | Yes | Configs for production deploys. |

