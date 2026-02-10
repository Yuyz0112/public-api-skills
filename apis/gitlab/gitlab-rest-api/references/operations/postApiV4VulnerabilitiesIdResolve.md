# POST /api/v4/vulnerabilities/{id}/resolve

**Resource:** [Vulnerabilities](../resources/Vulnerabilities.md)
**Resolve a vulnerability**
**Operation ID:** `postApiV4VulnerabilitiesIdResolve`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a vulnerability |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesVulnerability](../schemas/APIEntitiesVulnerability/APIEntitiesVulnerability.md)

