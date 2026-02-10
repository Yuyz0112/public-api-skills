# POST /api/v4/vulnerabilities/{id}/dismiss

**Resource:** [Vulnerabilities](../resources/Vulnerabilities.md)
**Dismiss a vulnerability**
**Operation ID:** `postApiV4VulnerabilitiesIdDismiss`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a vulnerability |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesVulnerability](../schemas/APIEntitiesVulnerability/APIEntitiesVulnerability.md)

