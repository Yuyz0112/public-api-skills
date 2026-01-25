# builds_BuildResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `build_outcome` | [builds_BuildOutcome](builds-BuildOutcome.md) | No |  |
| `build_trigger_metadata` | [builds_BuildTriggerMetadataResponse](builds-BuildTriggerMetadataResponse.md) | No |  |
| `build_uuid` | string (uuid) | No |  |
| `created_on` | string (date-time) | No |  |
| `initializing_on` | string (date-time) | No |  |
| `modified_on` | string (date-time) | No |  |
| `pull_request` | object | No |  |
| `running_on` | string (date-time) | No |  |
| `status` | [builds_BuildStatus](builds-BuildStatus.md) | No |  |
| `stopped_on` | string (date-time) | No |  |
| `trigger` | object | No | Trigger information without build_token_uuid |

## Nested Fields

### `pull_request`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created_on` | string (date-time) | No |  |
| `pull_request_url` | string (uri) | No |  |

### `trigger`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `branch_excludes` | string[] | No |  |
| `branch_includes` | string[] | No |  |
| `build_caching_enabled` | boolean | No |  |
| `build_command` | string | No |  |
| `created_on` | string (date-time) | No |  |
| `deleted_on` | string (date-time) | No |  |
| `deploy_command` | string | No |  |
| `external_script_id` | string | No |  |
| `modified_on` | string (date-time) | No |  |
| `path_excludes` | string[] | No |  |
| `path_includes` | string[] | No |  |
| `repo_connection` | [builds_UpsertRepoConnectionResponse](builds-UpsertRepoConnectionResponse.md) | No |  |
| `root_directory` | string | No |  |
| `trigger_name` | string | No |  |
| `trigger_uuid` | string (uuid) | No |  |

