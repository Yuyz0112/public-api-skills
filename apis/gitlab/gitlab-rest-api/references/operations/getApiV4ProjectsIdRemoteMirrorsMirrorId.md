# GET /api/v4/projects/{id}/remote_mirrors/{mirror_id}

**Resource:** [Remote mirrors](../resources/Remote-mirrors.md)
**Get a single remote mirror**
**Operation ID:** `getApiV4ProjectsIdRemoteMirrorsMirrorId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `mirror_id` | path | string | Yes | The ID of a remote mirror |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesRemoteMirror](../schemas/APIEntitiesRemoteMirror/APIEntitiesRemoteMirror.md)

