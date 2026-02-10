# GET /api/v4/issues/{id}

**Resource:** [Issues](../resources/Issues.md)
**Get specified issue (admin only)**
**Operation ID:** `getApiV4IssuesId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of the Issue |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesIssue](../schemas/APIEntitiesIssue/APIEntitiesIssue.md)

