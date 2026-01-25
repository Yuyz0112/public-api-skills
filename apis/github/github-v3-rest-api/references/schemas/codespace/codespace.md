# codespace

A codespace.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer (int64) | Yes |  |
| `name` | string | Yes | Automatically generated name of this codespace. |
| `display_name` | string | No | Display name for this codespace. |
| `environment_id` | string | Yes | UUID identifying this codespace's environment. |
| `owner` | [simple-user](simple-user.md) | Yes |  |
| `billable_owner` | [simple-user](simple-user.md) | Yes |  |
| `repository` | [minimal-repository](minimal-repository.md) | Yes |  |
| `machine` | [nullable-codespace-machine](nullable-codespace-machine.md) | Yes |  |
| `devcontainer_path` | string | No | Path to devcontainer.json from repo root used to create Codespace. |
| `prebuild` | boolean | Yes | Whether the codespace was created from a prebuild. |
| `created_at` | string (date-time) | Yes |  |
| `updated_at` | string (date-time) | Yes |  |
| `last_used_at` | string (date-time) | Yes | Last known time this codespace was started. |
| `state` | enum: Unknown, Created, Queued... | Yes | State of this codespace. |
| `url` | string (uri) | Yes | API URL for this codespace. |
| `git_status` | object | Yes | Details about the codespace's git repository. |
| `location` | enum: EastUs, SouthEastAsia, WestEurope... | Yes | The initally assigned location of a new codespace. |
| `idle_timeout_minutes` | integer | Yes | The number of minutes of inactivity after which this codespace will be automatically stopped. |
| `web_url` | string (uri) | Yes | URL to access this codespace on the web. |
| `machines_url` | string (uri) | Yes | API URL to access available alternate machine types for this codespace. |
| `start_url` | string (uri) | Yes | API URL to start this codespace. |
| `stop_url` | string (uri) | Yes | API URL to stop this codespace. |
| `publish_url` | string (uri) | No | API URL to publish this codespace to a new repository. |
| `pulls_url` | string (uri) | Yes | API URL for the Pull Request associated with this codespace, if any. |
| `recent_folders` | string[] | Yes |  |
| `runtime_constraints` | object | No |  |
| `pending_operation` | boolean | No | Whether or not a codespace has a pending async operation. This would mean that the codespace is temporarily unavailable. The only thing that you can do with a codespace in this state is delete it. |
| `pending_operation_disabled_reason` | string | No | Text to show user when codespace is disabled by a pending operation |
| `idle_timeout_notice` | string | No | Text to show user when codespace idle timeout minutes has been overriden by an organization policy |
| `retention_period_minutes` | integer | No | Duration in minutes after codespace has gone idle in which it will be deleted. Must be integer minutes between 0 and 43200 (30 days). |
| `retention_expires_at` | string (date-time) | No | When a codespace will be auto-deleted based on the "retention_period_minutes" and "last_used_at" |
| `last_known_stop_notice` | string | No | The text to display to a user when a codespace has been stopped for a potentially actionable reason. |

## Nested Fields

### `git_status`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `ahead` | integer | No | The number of commits the local repository is ahead of the remote. |
| `behind` | integer | No | The number of commits the local repository is behind the remote. |
| `has_unpushed_changes` | boolean | No | Whether the local repository has unpushed changes. |
| `has_uncommitted_changes` | boolean | No | Whether the local repository has uncommitted changes. |
| `ref` | string | No | The current branch (or SHA if in detached HEAD state) of the local repository. |

### `runtime_constraints`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `allowed_port_privacy_settings` | string[] | No | The privacy settings a user can select from when forwarding a port. |

