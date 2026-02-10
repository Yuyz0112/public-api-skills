# GET /api/v4/jobs/{id}/sbom_scans/{sbom_scan_id}

**Resource:** [Software composition analysis](../resources/Software-composition-analysis.md)
**Download an SBOM scan result file**
**Operation ID:** `getApiV4JobsIdSbomScansSbomScanId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | Job's ID |
| `sbom_scan_id` | path | integer | Yes | SBOM Scan's ID |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 202 | Sbom Scan in progress |
| 400 | Bad request |
| 403 | Forbidden |
| 410 | Sbom Scan failed |

**Success Response Schema:**

[APIEntitiesSecurityVulnerabilityScanningSbomScan](../schemas/APIEntitiesSecurityVulnerabilityScanningSbomScan/APIEntitiesSecurityVulnerabilityScanningSbomScan.md)

