# GET /api/v4/jobs/{id}/artifacts

**Resource:** [Jobs](../resources/Jobs.md)
**Download the artifacts file for job**
**Operation ID:** `getApiV4JobsIdArtifacts`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Job's ID |
| `token` | query | string | No | Job's authentication token |
| `direct_download` | query | boolean | No | Perform direct download from remote storage instead of proxying artifacts |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Download allowed |
| 302 | Found |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Artifact not found |
| 429 | Too Many Requests |

