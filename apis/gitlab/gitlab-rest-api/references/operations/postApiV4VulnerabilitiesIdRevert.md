# POST /api/v4/vulnerabilities/{id}/revert

**Resource:** [Vulnerabilities](../resources/Vulnerabilities.md)
**Revert a vulnerability to a detected state**
**Operation ID:** `postApiV4VulnerabilitiesIdRevert`

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

