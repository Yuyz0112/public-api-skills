# POST /api/v4/projects/{id}/issues/{issue_iid}/clone

**Resource:** [Projects](../resources/Projects.md)
**Clone an existing issue**
**Operation ID:** `postApiV4ProjectsIdIssuesIssueIidClone`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `issue_iid` | path | integer | Yes | The internal ID of a project issue |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesIssue](../schemas/APIEntitiesIssue/APIEntitiesIssue.md)

