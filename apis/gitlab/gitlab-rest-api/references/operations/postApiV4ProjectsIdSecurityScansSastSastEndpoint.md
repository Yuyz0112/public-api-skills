# POST /api/v4/projects/{id}/security_scans/sast/{sast_endpoint}

**Resource:** [Security scans](../resources/Security-scans.md)
**Scan a file for vulnerabilities. This feature is experimental.**
**Operation ID:** `postApiV4ProjectsIdSecurityScansSastSastEndpoint`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |

