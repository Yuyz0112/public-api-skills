# GET /api/v4/projects/{id}/packages/npm/*package_name/-/*file_name

**Resource:** [Packages](../resources/Packages.md)
**Download the NPM tarball**
**Operation ID:** `getApiV4ProjectsIdPackagesNpm*packageNameDash*fileName`

This feature was introduced in GitLab 11.8

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | query | string | Yes | Package name |
| `file_name` | query | string | Yes | Package file name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 403 | Forbidden |
| 404 | Not Found |

