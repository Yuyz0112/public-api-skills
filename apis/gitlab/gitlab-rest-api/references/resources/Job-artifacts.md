# Job artifacts

Operations related to job artifacts.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/jobs/artifacts/{ref_name}/download` | Download the artifacts archive from a job | [View](../operations/getApiV4ProjectsIdJobsArtifactsRefNameDownload.md) |
| GET | `/api/v4/projects/{id}/jobs/artifacts/{ref_name}/raw/*artifact_path` | Download a specific file from artifacts archive from a ref | [View](../operations/getApiV4ProjectsIdJobsArtifactsRefNameRaw-artifactPath.md) |
| GET | `/api/v4/projects/{id}/jobs/{job_id}/artifacts` | Download the artifacts archive from a job | [View](../operations/getApiV4ProjectsIdJobsJobIdArtifacts.md) |
| DELETE | `/api/v4/projects/{id}/jobs/{job_id}/artifacts` | Delete the artifacts files from a job | [View](../operations/deleteApiV4ProjectsIdJobsJobIdArtifacts.md) |
| GET | `/api/v4/projects/{id}/jobs/{job_id}/artifacts/tree` | List all files in the artifacts archive | [View](../operations/getApiV4ProjectsIdJobsJobIdArtifactsTree.md) |
| GET | `/api/v4/projects/{id}/jobs/{job_id}/artifacts/*artifact_path` | Download a specific file from artifacts archive | [View](../operations/getApiV4ProjectsIdJobsJobIdArtifacts-artifactPath.md) |
| POST | `/api/v4/projects/{id}/jobs/{job_id}/artifacts/keep` | Keep the artifacts to prevent them from being deleted | [View](../operations/postApiV4ProjectsIdJobsJobIdArtifactsKeep.md) |
| DELETE | `/api/v4/projects/{id}/artifacts` | Expire the artifacts files from a project | [View](../operations/deleteApiV4ProjectsIdArtifacts.md) |
