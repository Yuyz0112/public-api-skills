# DELETE /api/v4/projects/{id}/uploads/{upload_id}

**Resource:** [Projects](../resources/Projects.md)
**Delete a single project upload by ID**
**Operation ID:** `deleteApiV4ProjectsIdUploadsUploadId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `upload_id` | path | integer | Yes | The ID of a project upload |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad request |
| 403 | Unauthenticated |
| 404 | Not found |

