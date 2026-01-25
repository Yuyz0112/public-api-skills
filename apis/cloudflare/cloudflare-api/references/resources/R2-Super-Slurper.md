# R2 Super Slurper

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/slurper/jobs` | List jobs | [View](../operations/slurper-list-jobs.md) |
| POST | `/accounts/{account_id}/slurper/jobs` | Create a job | [View](../operations/slurper-create-job.md) |
| PUT | `/accounts/{account_id}/slurper/jobs/abortAll` | Abort all jobs | [View](../operations/slurper-abort-all-jobs.md) |
| GET | `/accounts/{account_id}/slurper/jobs/{job_id}` | Get job details | [View](../operations/slurper-get-job.md) |
| PUT | `/accounts/{account_id}/slurper/jobs/{job_id}/abort` | Abort a job | [View](../operations/slurper-abort-job.md) |
| GET | `/accounts/{account_id}/slurper/jobs/{job_id}/logs` | Get job logs | [View](../operations/slurper-get-job-logs.md) |
| PUT | `/accounts/{account_id}/slurper/jobs/{job_id}/pause` | Pause a job | [View](../operations/slurper-pause-job.md) |
| GET | `/accounts/{account_id}/slurper/jobs/{job_id}/progress` | Get job progress | [View](../operations/slurper-get-job-progress.md) |
| PUT | `/accounts/{account_id}/slurper/jobs/{job_id}/resume` | Resume a job | [View](../operations/slurper-resume-job.md) |
| PUT | `/accounts/{account_id}/slurper/source/connectivity-precheck` | Check source connectivity | [View](../operations/slurper-check-source-connectivity.md) |
| PUT | `/accounts/{account_id}/slurper/target/connectivity-precheck` | Check target connectivity | [View](../operations/slurper-check-target-connectivity.md) |
