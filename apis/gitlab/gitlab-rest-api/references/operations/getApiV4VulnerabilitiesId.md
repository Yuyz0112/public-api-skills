# GET /api/v4/vulnerabilities/{id}

**Resource:** [Vulnerabilities](../resources/Vulnerabilities.md)
**Get a vulnerability**
**Operation ID:** `getApiV4VulnerabilitiesId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a vulnerability |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesVulnerability](../schemas/APIEntitiesVulnerability/APIEntitiesVulnerability.md)

