# DELETE /api/v4/vulnerabilities/{id}/issue_links/{issue_link_id}

**Resource:** [Vulnerabilities](../resources/Vulnerabilities.md)
**Delete a link between an issue and a vulnerability**
**Operation ID:** `deleteApiV4VulnerabilitiesIdIssueLinksIssueLinkId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of a vulnerability |
| `issue_link_id` | path | integer | Yes | The ID of a vulnerability-issue-link to delete |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |

