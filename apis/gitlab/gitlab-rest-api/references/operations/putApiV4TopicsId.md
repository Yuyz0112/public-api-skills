# PUT /api/v4/topics/{id}

**Resource:** [Project topics](../resources/Project-topics.md)
**Update a topic**
**Operation ID:** `putApiV4TopicsId`

This feature was introduced in GitLab 14.5.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | ID of project topic |

## Request Body

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectsTopic](../schemas/APIEntitiesProjectsTopic/APIEntitiesProjectsTopic.md)

