# DELETE /api/v4/projects/{id}/uploads/{secret}/{filename}

**Resource:** [Projects](../resources/Projects.md)
**Delete a single project upload by secret and filename**
**Operation ID:** `deleteApiV4ProjectsIdUploadsSecretFilename`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `secret` | path | string | Yes | The 32-character secret of a project upload |
| `filename` | path | string | Yes | The filename of a project upload |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad request |
| 403 | Unauthenticated |
| 404 | Not found |

