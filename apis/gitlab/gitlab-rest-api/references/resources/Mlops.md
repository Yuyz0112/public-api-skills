# Mlops

Operations related to mlops.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow-artifacts/artifacts` | MLflow artifact API | [View](../operations/getApiV4ProjectsIdMlMlflowApi20MlflowArtifactsArtifacts.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/registered-models/create` | Creates a Registered Model. | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowRegisteredModelsCreate.md) |
| GET | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/registered-models/get` | Fetch a Registered Model by Name | [View](../operations/getApiV4ProjectsIdMlMlflowApi20MlflowRegisteredModelsGet.md) |
| PATCH | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/registered-models/update` | Update a Registered Model by Name | [View](../operations/patchApiV4ProjectsIdMlMlflowApi20MlflowRegisteredModelsUpdate.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/registered-models/get-latest-versions` | Fetch the latest Model Version for the given Registered Model Name | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowRegisteredModelsGetLatestVersions.md) |
| DELETE | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/registered-models/delete` | Delete a Registered Model by Name | [View](../operations/deleteApiV4ProjectsIdMlMlflowApi20MlflowRegisteredModelsDelete.md) |
| GET | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/registered-models/search` | Search Registered Models within a project | [View](../operations/getApiV4ProjectsIdMlMlflowApi20MlflowRegisteredModelsSearch.md) |
| GET | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/registered-models/alias` | Gets a Model Version by alias | [View](../operations/getApiV4ProjectsIdMlMlflowApi20MlflowRegisteredModelsAlias.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/runs/create` | Creates a Run. | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowRunsCreate.md) |
| GET | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/runs/get` | Gets an MLFlow Run, which maps to GitLab Candidates | [View](../operations/getApiV4ProjectsIdMlMlflowApi20MlflowRunsGet.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/runs/search` | Searches runs/candidates within a project | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowRunsSearch.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/runs/update` | Updates a Run. | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowRunsUpdate.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/runs/log-metric` | Logs a metric to a run. | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowRunsLogMetric.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/runs/log-parameter` | Logs a parameter to a run. | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowRunsLogParameter.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/runs/set-tag` | Sets a tag for a run. | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowRunsSetTag.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/runs/log-batch` | Logs multiple parameters and metrics. | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowRunsLogBatch.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/runs/delete` | Delete a run. | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowRunsDelete.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/model-versions/create` | Creates a Model Version. | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowModelVersionsCreate.md) |
| GET | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/model-versions/get-download-uri` | Fetch the download URI for the model version. | [View](../operations/getApiV4ProjectsIdMlMlflowApi20MlflowModelVersionsGetDownloadUri.md) |
| GET | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/model-versions/get` | Fetch model version by name and version | [View](../operations/getApiV4ProjectsIdMlMlflowApi20MlflowModelVersionsGet.md) |
| PATCH | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/model-versions/update` | Updates a Model Version. | [View](../operations/patchApiV4ProjectsIdMlMlflowApi20MlflowModelVersionsUpdate.md) |
| GET | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/experiments/get` | Fetch experiment by experiment_id | [View](../operations/getApiV4ProjectsIdMlMlflowApi20MlflowExperimentsGet.md) |
| GET | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/experiments/get-by-name` | Fetch experiment by experiment_name | [View](../operations/getApiV4ProjectsIdMlMlflowApi20MlflowExperimentsGetByName.md) |
| GET | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/experiments/list` | List experiments | [View](../operations/getApiV4ProjectsIdMlMlflowApi20MlflowExperimentsList.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/experiments/search` | Search experiments | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowExperimentsSearch.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/experiments/create` | Create experiment | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowExperimentsCreate.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/experiments/set-experiment-tag` | Sets a tag for an experiment. | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowExperimentsSetExperimentTag.md) |
| POST | `/api/v4/projects/{id}/ml/mlflow/api/2.0/mlflow/experiments/delete` | Delete an experiment. | [View](../operations/postApiV4ProjectsIdMlMlflowApi20MlflowExperimentsDelete.md) |
