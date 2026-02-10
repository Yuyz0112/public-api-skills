# GET /api/v4/projects/{id}/uploads/{secret}/{filename}

**Resource:** [Projects](../resources/Projects.md)
**Download a single project upload by secret and filename**
**Operation ID:** `getApiV4ProjectsIdUploadsSecretFilename`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `secret` | path | string | Yes | The 32-character secret of a project upload |
| `filename` | path | string | Yes | The filename of a project upload |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Unauthenticated |
| 404 | Not found |

