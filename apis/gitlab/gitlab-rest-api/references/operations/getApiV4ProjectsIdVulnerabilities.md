# GET /api/v4/projects/{id}/vulnerabilities

**Resource:** [Vulnerabilities](../resources/Vulnerabilities.md)
**Get a list of project vulnerabilities**
**Operation ID:** `getApiV4ProjectsIdVulnerabilities`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesVulnerability](../schemas/APIEntitiesVulnerability/APIEntitiesVulnerability.md)

