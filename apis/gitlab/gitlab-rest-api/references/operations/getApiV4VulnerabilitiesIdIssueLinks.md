# GET /api/v4/vulnerabilities/{id}/issue_links

**Resource:** [Vulnerabilities](../resources/Vulnerabilities.md)
**Get related issues for a vulnerability**
**Operation ID:** `getApiV4VulnerabilitiesIdIssueLinks`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of a vulnerability |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesVulnerabilityRelatedIssue](../schemas/APIEntitiesVulnerabilityRelatedIssue/APIEntitiesVulnerabilityRelatedIssue.md)

