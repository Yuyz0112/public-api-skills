# code-scanning-variant-analysis

A run of a CodeQL query against one or more repositories.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | The ID of the variant analysis. |
| `controller_repo` | [simple-repository](simple-repository.md) | Yes |  |
| `actor` | [simple-user](simple-user.md) | Yes |  |
| `query_language` | [code-scanning-variant-analysis-language](code-scanning-variant-analysis-language.md) | Yes |  |
| `query_pack_url` | string | Yes | The download url for the query pack. |
| `created_at` | string (date-time) | No | The date and time at which the variant analysis was created, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. |
| `updated_at` | string (date-time) | No | The date and time at which the variant analysis was last updated, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. |
| `completed_at` | string (date-time) | No | The date and time at which the variant analysis was completed, in ISO 8601 format':' YYYY-MM-DDTHH:MM:SSZ. Will be null if the variant analysis has not yet completed or this information is not available. |
| `status` | enum: in_progress, succeeded, failed... | Yes |  |
| `actions_workflow_run_id` | integer | No | The GitHub Actions workflow run used to execute this variant analysis. This is only available if the workflow run has started. |
| `failure_reason` | enum: no_repos_queried, actions_workflow_run_failed, internal_error | No | The reason for a failure of the variant analysis. This is only available if the variant analysis has failed. |
| `scanned_repositories` | object[] | No |  |
| `skipped_repositories` | object | No | Information about repositories that were skipped from processing. This information is only available to the user that initiated the variant analysis. |

## Nested Fields

### `scanned_repositories`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `repository` | [code-scanning-variant-analysis-repository](code-scanning-variant-analysis-repository.md) | Yes |  |
| `analysis_status` | [code-scanning-variant-analysis-status](code-scanning-variant-analysis-status.md) | Yes |  |
| `result_count` | integer | No | The number of results in the case of a successful analysis. This is only available for successful analyses. |
| `artifact_size_in_bytes` | integer | No | The size of the artifact. This is only available for successful analyses. |
| `failure_message` | string | No | The reason of the failure of this repo task. This is only available if the repository task has failed. |

### `skipped_repositories`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `access_mismatch_repos` | [code-scanning-variant-analysis-skipped-repo-group](code-scanning-variant-analysis-skipped-repo-group.md) | Yes |  |
| `not_found_repos` | object | Yes |  |
| `no_codeql_db_repos` | [code-scanning-variant-analysis-skipped-repo-group](code-scanning-variant-analysis-skipped-repo-group.md) | Yes |  |
| `over_limit_repos` | [code-scanning-variant-analysis-skipped-repo-group](code-scanning-variant-analysis-skipped-repo-group.md) | Yes |  |

#### `skipped_repositories.not_found_repos`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `repository_count` | integer | Yes | The total number of repositories that were skipped for this reason. |
| `repository_full_names` | string[] | Yes | A list of full repository names that were skipped. This list may not include all repositories that were skipped. |

