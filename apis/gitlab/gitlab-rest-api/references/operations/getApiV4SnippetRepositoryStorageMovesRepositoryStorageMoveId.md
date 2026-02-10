# GET /api/v4/snippet_repository_storage_moves/{repository_storage_move_id}

**Resource:** [snippet_repository_storage_moves](../resources/snippet-repository-storage-moves.md)
**Get a snippet repository storage move**
**Operation ID:** `getApiV4SnippetRepositoryStorageMovesRepositoryStorageMoveId`

This feature was introduced in GitLab 13.8.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repository_storage_move_id` | path | integer | Yes | The ID of a snippet repository storage move |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSnippetsRepositoryStorageMove](../schemas/APIEntitiesSnippetsRepositoryStorageMove/APIEntitiesSnippetsRepositoryStorageMove.md)

