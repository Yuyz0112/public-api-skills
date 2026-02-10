# GET /api/v4/projects/{id}/issues/{issue_iid}/user_agent_detail

**Resource:** [Issues](../resources/Issues.md)
**Get the user agent details for an issue**
**Operation ID:** `getApiV4ProjectsIdIssuesIssueIidUserAgentDetail`

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

[APIEntitiesUserAgentDetail](../schemas/APIEntitiesUserAgentDetail/APIEntitiesUserAgentDetail.md)

