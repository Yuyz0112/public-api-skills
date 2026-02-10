# POST /api/v4/jobs/{id}/artifacts

**Resource:** [Jobs](../resources/Jobs.md)
**Upload a job artifact**
**Operation ID:** `postApiV4JobsIdArtifacts`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Job's ID |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Artifact uploaded |
| 400 | Bad request |
| 403 | Forbidden |
| 405 | Artifacts support not enabled |
| 413 | File too large |
| 429 | Too Many Requests |

