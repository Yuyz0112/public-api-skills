# POST /api/v4/vulnerabilities/{id}/issue_links

**Resource:** [Vulnerabilities](../resources/Vulnerabilities.md)
**Relate an issue to a vulnerability**
**Operation ID:** `postApiV4VulnerabilitiesIdIssueLinks`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of a vulnerability |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesVulnerabilityIssueLink](../schemas/APIEntitiesVulnerabilityIssueLink/APIEntitiesVulnerabilityIssueLink.md)

