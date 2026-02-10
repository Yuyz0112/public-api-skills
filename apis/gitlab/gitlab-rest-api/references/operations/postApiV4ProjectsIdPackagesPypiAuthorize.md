# POST /api/v4/projects/{id}/packages/pypi/authorize

**Resource:** [Packages](../resources/Packages.md)
**Authorize the PyPi package upload from workhorse**
**Operation ID:** `postApiV4ProjectsIdPackagesPypiAuthorize`

This feature was introduced in GitLab 12.10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

