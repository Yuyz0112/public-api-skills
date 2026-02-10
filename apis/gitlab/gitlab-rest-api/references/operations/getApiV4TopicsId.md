# GET /api/v4/topics/{id}

**Resource:** [Project topics](../resources/Project-topics.md)
**Get topic**
**Operation ID:** `getApiV4TopicsId`

This feature was introduced in GitLab 14.5.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | ID of project topic |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectsTopic](../schemas/APIEntitiesProjectsTopic/APIEntitiesProjectsTopic.md)

