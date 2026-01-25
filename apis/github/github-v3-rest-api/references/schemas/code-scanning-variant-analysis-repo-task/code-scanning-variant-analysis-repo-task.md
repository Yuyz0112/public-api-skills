# code-scanning-variant-analysis-repo-task

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `repository` | [simple-repository](simple-repository.md) | Yes |  |
| `analysis_status` | [code-scanning-variant-analysis-status](code-scanning-variant-analysis-status.md) | Yes |  |
| `artifact_size_in_bytes` | integer | No | The size of the artifact. This is only available for successful analyses. |
| `result_count` | integer | No | The number of results in the case of a successful analysis. This is only available for successful analyses. |
| `failure_message` | string | No | The reason of the failure of this repo task. This is only available if the repository task has failed. |
| `database_commit_sha` | string | No | The SHA of the commit the CodeQL database was built against. This is only available for successful analyses. |
| `source_location_prefix` | string | No | The source location prefix to use. This is only available for successful analyses. |
| `artifact_url` | string | No | The URL of the artifact. This is only available for successful analyses. |

