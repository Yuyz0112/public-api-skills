# GET /repos/{owner}/{repo}/actions/artifacts/{artifact_id}/{archive_format}

**Resource:** [actions](../resources/actions.md)
**Download an artifact**
**Operation ID:** `actions/download-artifact`

Gets a redirect URL to download an archive for a repository. This URL expires after 1 minute. Look for `Location:` in
the response header to find the URL for the download. The `:archive_format` must be `zip`.

OAuth tokens and personal access tokens (classic) need the `repo` scope to use this endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `archive_format` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 302 | Response |
| 410 | (reference) |

