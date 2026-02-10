# POST /api/v4/projects/{id}/remote_mirrors/{mirror_id}/sync

**Resource:** [Remote mirrors](../resources/Remote-mirrors.md)
**Triggers a push mirror operation**
**Operation ID:** `postApiV4ProjectsIdRemoteMirrorsMirrorIdSync`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `mirror_id` | path | string | Yes | The ID of a remote mirror |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad request |
| 401 | Unauthorized |
| 404 | Not found |

