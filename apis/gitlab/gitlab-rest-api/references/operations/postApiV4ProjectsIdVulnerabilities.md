# POST /api/v4/projects/{id}/vulnerabilities

**Resource:** [Vulnerabilities](../resources/Vulnerabilities.md)
**Create a new Vulnerability (from a confirmed Finding)**
**Operation ID:** `postApiV4ProjectsIdVulnerabilities`

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
| 201 | Created |

**Success Response Schema:**

[APIEntitiesVulnerability](../schemas/APIEntitiesVulnerability/APIEntitiesVulnerability.md)

