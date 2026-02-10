# GET /api/v4/projects/{id}/issues/{issue_iid}/links/{issue_link_id}

**Resource:** [Issues](../resources/Issues.md)
**Get an issue link**
**Operation ID:** `getApiV4ProjectsIdIssuesIssueIidLinksIssueLinkId`

Gets details about an issue link. This feature was introduced in GitLab 15.1.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `issue_iid` | path | integer | Yes | The internal ID of a project’s issue |
| `issue_link_id` | path | any | Yes | ID of an issue relationship |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesIssueLink](../schemas/APIEntitiesIssueLink/APIEntitiesIssueLink.md)

