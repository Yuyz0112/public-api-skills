# POST /api/v4/groups/{id}/repository_storage_moves

**Resource:** [groups](../resources/groups.md)
**Schedule a group repository storage move**
**Operation ID:** `postApiV4GroupsIdRepositoryStorageMoves`

This feature was introduced in GitLab 13.9.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesGroupsRepositoryStorageMove](../schemas/APIEntitiesGroupsRepositoryStorageMove/APIEntitiesGroupsRepositoryStorageMove.md)

