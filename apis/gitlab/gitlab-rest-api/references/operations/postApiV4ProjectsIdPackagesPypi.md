# POST /api/v4/projects/{id}/packages/pypi

**Resource:** [Packages](../resources/Packages.md)
**The PyPi Package upload endpoint**
**Operation ID:** `postApiV4ProjectsIdPackagesPypi`

This feature was introduced in GitLab 12.10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `multipart/form-data`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |
| 422 | Unprocessable Entity |

