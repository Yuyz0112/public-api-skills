# DELETE /api/v4/projects/{id}/issues/{issue_iid}/links/{issue_link_id}

**Resource:** [Issues](../resources/Issues.md)
**Delete an issue link**
**Operation ID:** `deleteApiV4ProjectsIdIssuesIssueIidLinksIssueLinkId`

Deletes an issue link, thus removes the two-way relationship.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `issue_iid` | path | integer | Yes | The internal ID of a project’s issue |
| `issue_link_id` | path | any | Yes | The ID of an issue relationship |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 404 | Not found |

