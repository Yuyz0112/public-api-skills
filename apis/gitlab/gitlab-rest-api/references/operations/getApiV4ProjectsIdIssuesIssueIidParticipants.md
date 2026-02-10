# GET /api/v4/projects/{id}/issues/{issue_iid}/participants

**Resource:** [Issues](../resources/Issues.md)
**List participants for an issue**
**Operation ID:** `getApiV4ProjectsIdIssuesIssueIidParticipants`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `issue_iid` | path | integer | Yes | The internal ID of a project issue |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesUserBasic](../schemas/APIEntitiesUserBasic/APIEntitiesUserBasic.md)

