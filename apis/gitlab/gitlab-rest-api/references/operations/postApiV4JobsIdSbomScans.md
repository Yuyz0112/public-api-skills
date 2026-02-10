# POST /api/v4/jobs/{id}/sbom_scans

**Resource:** [Software composition analysis](../resources/Software-composition-analysis.md)
**Upload an SBOM file to be scanned**
**Operation ID:** `postApiV4JobsIdSbomScans`

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
| 201 | Created |
| 400 | Bad request |
| 403 | Forbidden |
| 413 | File too large |

**Success Response Schema:**

[APIEntitiesSecurityVulnerabilityScanningSbomScan](../schemas/APIEntitiesSecurityVulnerabilityScanningSbomScan/APIEntitiesSecurityVulnerabilityScanningSbomScan.md)

