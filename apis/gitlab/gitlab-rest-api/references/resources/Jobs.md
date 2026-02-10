# Jobs

Operations related to jobs.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/runners/{id}/jobs` | List jobs running on a runner | [View](../operations/getApiV4RunnersIdJobs.md) |
| POST | `/api/v4/jobs/request` | Request a job | [View](../operations/postApiV4JobsRequest.md) |
| PUT | `/api/v4/jobs/{id}` | Update a job | [View](../operations/putApiV4JobsId.md) |
| PATCH | `/api/v4/jobs/{id}/trace` | Append a patch to the job trace | [View](../operations/patchApiV4JobsIdTrace.md) |
| POST | `/api/v4/jobs/{id}/artifacts/authorize` | Authorize uploading job artifact | [View](../operations/postApiV4JobsIdArtifactsAuthorize.md) |
| GET | `/api/v4/jobs/{id}/artifacts` | Download the artifacts file for job | [View](../operations/getApiV4JobsIdArtifacts.md) |
| POST | `/api/v4/jobs/{id}/artifacts` | Upload a job artifact | [View](../operations/postApiV4JobsIdArtifacts.md) |
