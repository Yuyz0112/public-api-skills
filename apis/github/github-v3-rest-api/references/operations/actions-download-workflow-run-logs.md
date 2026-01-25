# GET /repos/{owner}/{repo}/actions/runs/{run_id}/logs

**Resource:** [actions](../resources/actions.md)
**Download workflow run logs**
**Operation ID:** `actions/download-workflow-run-logs`

Gets a redirect URL to download an archive of log files for a workflow run. This link expires after 1 minute. Look for
`Location:` in the response header to find the URL for the download.

Anyone with read access to the repository can use this endpoint.

If the repository is private, OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Responses

| Status | Description |
|--------|-------------|
| 302 | Response |

