# POST /api/v4/jobs/{id}/sbom_scans/authorize

**Resource:** [Software composition analysis](../resources/Software-composition-analysis.md)
**Authorize uploading SBOM file to be scanned**
**Operation ID:** `postApiV4JobsIdSbomScansAuthorize`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Job's ID |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 413 | File too large |

