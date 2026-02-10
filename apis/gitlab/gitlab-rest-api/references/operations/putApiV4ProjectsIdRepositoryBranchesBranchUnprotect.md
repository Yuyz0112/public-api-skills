# PUT /api/v4/projects/{id}/repository/branches/{branch}/unprotect

**Resource:** [Branches](../resources/Branches.md)
**Unprotect a single branch**
**Operation ID:** `putApiV4ProjectsIdRepositoryBranchesBranchUnprotect`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `branch` | path | string | Yes | The name of the branch |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | 404 Branch Not Found |

**Success Response Schema:**

[APIEntitiesBranch](../schemas/APIEntitiesBranch/APIEntitiesBranch.md)

