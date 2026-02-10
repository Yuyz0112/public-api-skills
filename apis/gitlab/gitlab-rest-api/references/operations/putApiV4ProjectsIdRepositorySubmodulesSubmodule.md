# PUT /api/v4/projects/{id}/repository/submodules/{submodule}

**Resource:** [Submodules](../resources/Submodules.md)
**Update existing submodule reference in repository**
**Operation ID:** `putApiV4ProjectsIdRepositorySubmodulesSubmodule`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID or URL-encoded path of a project |
| `submodule` | path | string | Yes | URL-encoded full path to submodule. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | The repository is empty |
| 401 | 401 Unauthorized |
| 404 | 404 Project Not Found |

**Success Response Schema:**

[APIEntitiesCommitDetail](../schemas/APIEntitiesCommitDetail/APIEntitiesCommitDetail.md)

