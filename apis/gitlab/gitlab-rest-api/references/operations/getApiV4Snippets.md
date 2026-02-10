# GET /api/v4/snippets

**Resource:** [Snippets](../resources/Snippets.md)
**Get a snippets list for an authenticated user**
**Operation ID:** `getApiV4Snippets`

This feature was introduced in GitLab 8.15.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created_after` | query | string (date-time) | No | Return snippets created after the specified time |
| `created_before` | query | string (date-time) | No | Return snippets created before the specified time |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesSnippet](../schemas/APIEntitiesSnippet/APIEntitiesSnippet.md)

