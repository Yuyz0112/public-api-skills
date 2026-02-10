# GET /api/v4/projects/{id}/repository/branches/{branch}

**Resource:** [Branches](../resources/Branches.md)
**Get a single repository branch**
**Operation ID:** `getApiV4ProjectsIdRepositoryBranchesBranch`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Project Not Found |

**Success Response Schema:**

[APIEntitiesBranch](../schemas/APIEntitiesBranch/APIEntitiesBranch.md)

