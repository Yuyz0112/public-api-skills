# PUT /api/v4/projects/{id}/remote_mirrors/{mirror_id}

**Resource:** [Remote mirrors](../resources/Remote-mirrors.md)
**Update the attributes of a single remote mirror**
**Operation ID:** `putApiV4ProjectsIdRemoteMirrorsMirrorId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `mirror_id` | path | string | Yes | The ID of a remote mirror |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesRemoteMirror](../schemas/APIEntitiesRemoteMirror/APIEntitiesRemoteMirror.md)

