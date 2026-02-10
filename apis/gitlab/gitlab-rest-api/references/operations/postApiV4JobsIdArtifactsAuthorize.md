# POST /api/v4/jobs/{id}/artifacts/authorize

**Resource:** [Jobs](../resources/Jobs.md)
**Authorize uploading job artifact**
**Operation ID:** `postApiV4JobsIdArtifactsAuthorize`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Job's ID |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Upload allowed |
| 403 | Forbidden |
| 405 | Artifacts support not enabled |
| 413 | File too large |
| 429 | Too Many Requests |

