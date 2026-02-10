# GET /api/v4/snippets/{id}/repository_storage_moves

**Resource:** [snippets](../resources/snippets.md)
**Get a list of all snippets repository storage moves**
**Operation ID:** `getApiV4SnippetsIdRepositoryStorageMoves`

This feature was introduced in GitLab 13.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a snippet |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSnippetsRepositoryStorageMove](../schemas/APIEntitiesSnippetsRepositoryStorageMove/APIEntitiesSnippetsRepositoryStorageMove.md)

