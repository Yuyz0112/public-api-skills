# PUT /api/v4/projects/{id}/issues/{issue_iid}/reorder

**Resource:** [Projects](../resources/Projects.md)
**Reorder an existing issue**
**Operation ID:** `putApiV4ProjectsIdIssuesIssueIidReorder`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `issue_iid` | path | integer | Yes | The internal ID of a project issue |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesIssue](../schemas/APIEntitiesIssue/APIEntitiesIssue.md)

