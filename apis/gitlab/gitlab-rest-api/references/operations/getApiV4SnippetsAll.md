# GET /api/v4/snippets/all

**Resource:** [Snippets](../resources/Snippets.md)
**List all snippets current_user has access to**
**Operation ID:** `getApiV4SnippetsAll`

This feature was introduced in GitLab 16.3.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `created_after` | query | string (date-time) | No | Return snippets created after the specified time |
| `created_before` | query | string (date-time) | No | Return snippets created before the specified time |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `repository_storage` | query | string | No | Filter by repository storage used by the snippet |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesSnippet](../schemas/APIEntitiesSnippet/APIEntitiesSnippet.md)

