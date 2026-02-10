# GET /api/v4/projects/{id}/packages/pypi/files/{sha256}/*file_identifier

**Resource:** [Packages](../resources/Packages.md)
**The PyPi package download endpoint**
**Operation ID:** `getApiV4ProjectsIdPackagesPypiFilesSha256*fileIdentifier`

This feature was introduced in GitLab 12.10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `file_identifier` | query | string | Yes | The PyPi package file identifier |
| `sha256` | path | string | Yes | The PyPi package sha256 check sum |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

