# GET /api/v4/projects/{id}/issues/{issue_iid}/links

**Resource:** [Issues](../resources/Issues.md)
**List issue relations**
**Operation ID:** `getApiV4ProjectsIdIssuesIssueIidLinks`

Get a list of a given issue’s linked issues, sorted by the relationship creation datetime (ascending).Issues are filtered according to the user authorizations.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `issue_iid` | path | integer | Yes | The internal ID of a project’s issue |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesRelatedIssue](../schemas/APIEntitiesRelatedIssue/APIEntitiesRelatedIssue.md)

