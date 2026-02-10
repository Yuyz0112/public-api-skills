# CI jobs

Operations related to CI jobs.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/jobs` | Get a projects jobs | [View](../operations/getApiV4ProjectsIdJobs.md) |
| GET | `/api/v4/projects/{id}/jobs/{job_id}` | Get a specific job of a project | [View](../operations/getApiV4ProjectsIdJobsJobId.md) |
| GET | `/api/v4/projects/{id}/jobs/{job_id}/trace` | Get a trace of a specific job of a project | [View](../operations/getApiV4ProjectsIdJobsJobIdTrace.md) |
| POST | `/api/v4/projects/{id}/jobs/{job_id}/cancel` | Cancel a specific job of a project | [View](../operations/postApiV4ProjectsIdJobsJobIdCancel.md) |
| POST | `/api/v4/projects/{id}/jobs/{job_id}/retry` | Retry a specific job of a project | [View](../operations/postApiV4ProjectsIdJobsJobIdRetry.md) |
| POST | `/api/v4/projects/{id}/jobs/{job_id}/erase` | Erase job (remove artifacts and the trace) | [View](../operations/postApiV4ProjectsIdJobsJobIdErase.md) |
| POST | `/api/v4/projects/{id}/jobs/{job_id}/play` | Trigger an actionable job (manual, delayed, etc) | [View](../operations/postApiV4ProjectsIdJobsJobIdPlay.md) |
| GET | `/api/v4/job` | Get current job using job token | [View](../operations/getApiV4Job.md) |
