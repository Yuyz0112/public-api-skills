# POST /api/v4/groups/{id}/projects/{project_id}

**Resource:** [Groups](../resources/Groups.md)
**Transfer a project to the group namespace. Available only for admin.**
**Operation ID:** `postApiV4GroupsIdProjectsProjectId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a group |
| `project_id` | path | string | Yes | The ID or path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

**Success Response Schema:**

[APIEntitiesGroupDetail](../schemas/APIEntitiesGroupDetail/APIEntitiesGroupDetail.md)

