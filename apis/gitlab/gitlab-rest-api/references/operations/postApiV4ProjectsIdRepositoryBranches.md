# POST /api/v4/projects/{id}/repository/branches

**Resource:** [Branches](../resources/Branches.md)
**Create branch**
**Operation ID:** `postApiV4ProjectsIdRepositoryBranches`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Branch already exists |

**Success Response Schema:**

[APIEntitiesBranch](../schemas/APIEntitiesBranch/APIEntitiesBranch.md)

