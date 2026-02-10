# POST /api/v4/projects/{id}/issues/{issue_iid}/links

**Resource:** [Issues](../resources/Issues.md)
**Create an issue link**
**Operation ID:** `postApiV4ProjectsIdIssuesIssueIidLinks`

Creates a two-way relation between two issues.The user must be allowed to update both issues to succeed.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project owned by the authenticated user |
| `issue_iid` | path | integer | Yes | The internal ID of a project’s issue |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |

**Success Response Schema:**

[APIEntitiesIssueLink](../schemas/APIEntitiesIssueLink/APIEntitiesIssueLink.md)

