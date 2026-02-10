# projects

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| PATCH | `/api/v4/projects/{id}/compliance_external_controls/{control_id}/status` | Update the status of a control | [View](../operations/patchApiV4ProjectsIdComplianceExternalControlsControlIdStatus.md) |
| POST | `/api/v4/projects/{id}/dependency_list_exports` | Generate a dependency list export on a project-level | [View](../operations/postApiV4ProjectsIdDependencyListExports.md) |
| POST | `/api/v4/projects/{project_id}/product_analytics/request/load` | Proxy analytics request to cube installation.
            Requires :product_analytics_features flag to be enabled. | [View](../operations/postApiV4ProjectsProjectIdProductAnalyticsRequestLoad.md) |
| POST | `/api/v4/projects/{project_id}/product_analytics/request/dry-run` |  | [View](../operations/postApiV4ProjectsProjectIdProductAnalyticsRequestDryRun.md) |
| POST | `/api/v4/projects/{project_id}/product_analytics/request/meta` |  | [View](../operations/postApiV4ProjectsProjectIdProductAnalyticsRequestMeta.md) |
| POST | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/blocks` |  | [View](../operations/postApiV4ProjectsIdMergeRequestsMergeRequestIidBlocks.md) |
| GET | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/blocks/{block_id}` |  | [View](../operations/getApiV4ProjectsIdMergeRequestsMergeRequestIidBlocksBlockId.md) |
| DELETE | `/api/v4/projects/{id}/merge_requests/{merge_request_iid}/blocks/{block_id}` |  | [View](../operations/deleteApiV4ProjectsIdMergeRequestsMergeRequestIidBlocksBlockId.md) |
| GET | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow-artifacts/artifacts/{model_version}/*file_path` |  | [View](../operations/getApiV4ProjectsIdMlMlflowApi20MlflowArtifactsArtifactsModelVersion-filePath.md) |
| GET | `/api/v4/projects/{id}/repository_storage_moves` | Get a list of all project repository storage moves | [View](../operations/getApiV4ProjectsIdRepositoryStorageMoves.md) |
| POST | `/api/v4/projects/{id}/repository_storage_moves` | Schedule a project repository storage move | [View](../operations/postApiV4ProjectsIdRepositoryStorageMoves.md) |
| GET | `/api/v4/projects/{id}/repository_storage_moves/{repository_storage_move_id}` | Get a project repository storage move | [View](../operations/getApiV4ProjectsIdRepositoryStorageMovesRepositoryStorageMoveId.md) |
| PUT | `/api/v4/projects/{id}/hooks/{hook_id}/url_variables/{key}` | Set a url variable | [View](../operations/putApiV4ProjectsIdHooksHookIdUrlVariablesKey.md) |
| DELETE | `/api/v4/projects/{id}/hooks/{hook_id}/url_variables/{key}` | Un-Set a url variable | [View](../operations/deleteApiV4ProjectsIdHooksHookIdUrlVariablesKey.md) |
| PUT | `/api/v4/projects/{id}/hooks/{hook_id}/custom_headers/{key}` | Set a custom header | [View](../operations/putApiV4ProjectsIdHooksHookIdCustomHeadersKey.md) |
| DELETE | `/api/v4/projects/{id}/hooks/{hook_id}/custom_headers/{key}` | Un-Set a custom header | [View](../operations/deleteApiV4ProjectsIdHooksHookIdCustomHeadersKey.md) |
| POST | `/api/v4/projects/{id}/create_ci_config` | Creates merge request for missing ci config in project | [View](../operations/postApiV4ProjectsIdCreateCiConfig.md) |
| POST | `/api/v4/projects/{id}/issues/{issue_iid}/metric_images/authorize` |  | [View](../operations/postApiV4ProjectsIdIssuesIssueIidMetricImagesAuthorize.md) |
