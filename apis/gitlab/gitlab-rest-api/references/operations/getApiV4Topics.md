# GET /api/v4/topics

**Resource:** [Project topics](../resources/Project-topics.md)
**Get topics**
**Operation ID:** `getApiV4Topics`

This feature was introduced in GitLab 14.5.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `search` | query | string | No | Return list of topics matching the search criteria |
| `without_projects` | query | boolean | No | Return list of topics without assigned projects |
| `organization_id` | query | integer | No | The organization id for the topics |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesProjectsTopic](../schemas/APIEntitiesProjectsTopic/APIEntitiesProjectsTopic.md)

