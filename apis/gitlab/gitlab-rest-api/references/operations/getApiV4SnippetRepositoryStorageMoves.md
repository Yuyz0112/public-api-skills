# GET /api/v4/snippet_repository_storage_moves

**Resource:** [snippet_repository_storage_moves](../resources/snippet-repository-storage-moves.md)
**Get a list of all snippet repository storage moves**
**Operation ID:** `getApiV4SnippetRepositoryStorageMoves`

This feature was introduced in GitLab 13.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSnippetsRepositoryStorageMove](../schemas/APIEntitiesSnippetsRepositoryStorageMove/APIEntitiesSnippetsRepositoryStorageMove.md)

