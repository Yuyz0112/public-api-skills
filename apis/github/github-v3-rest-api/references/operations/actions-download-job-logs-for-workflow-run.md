# GET /repos/{owner}/{repo}/actions/jobs/{job_id}/logs

**Resource:** [actions](../resources/actions.md)
**Download job logs for a workflow run**
**Operation ID:** `actions/download-job-logs-for-workflow-run`

Gets a redirect URL to download a plain text file of logs for a workflow job. This link expires after 1 minute. Look
for `Location:` in the response header to find the URL for the download.

Anyone with read access to the repository can use this endpoint.

If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 302 | Response |

