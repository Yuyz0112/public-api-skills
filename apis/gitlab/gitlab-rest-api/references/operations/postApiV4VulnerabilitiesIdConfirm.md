# POST /api/v4/vulnerabilities/{id}/confirm

**Resource:** [Vulnerabilities](../resources/Vulnerabilities.md)
**Confirm a vulnerability**
**Operation ID:** `postApiV4VulnerabilitiesIdConfirm`

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

