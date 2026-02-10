# DELETE /api/v4/projects/{id}/remote_mirrors/{mirror_id}

**Resource:** [Remote mirrors](../resources/Remote-mirrors.md)
**Delete a single remote mirror**
**Operation ID:** `deleteApiV4ProjectsIdRemoteMirrorsMirrorId`

This feature was introduced in GitLab 14.10

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

