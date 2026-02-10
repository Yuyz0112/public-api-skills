# POST /api/v4/projects/{id}/remote_mirrors

**Resource:** [Remote mirrors](../resources/Remote-mirrors.md)
**Create remote mirror for a project**
**Operation ID:** `postApiV4ProjectsIdRemoteMirrors`

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
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesRemoteMirror](../schemas/APIEntitiesRemoteMirror/APIEntitiesRemoteMirror.md)

