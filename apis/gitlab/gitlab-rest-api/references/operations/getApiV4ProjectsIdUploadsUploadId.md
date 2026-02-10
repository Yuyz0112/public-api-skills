# GET /api/v4/projects/{id}/uploads/{upload_id}

**Resource:** [Projects](../resources/Projects.md)
**Download a single project upload by ID**
**Operation ID:** `getApiV4ProjectsIdUploadsUploadId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `upload_id` | path | integer | Yes | The ID of a project upload |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Unauthenticated |
| 404 | Not found |

