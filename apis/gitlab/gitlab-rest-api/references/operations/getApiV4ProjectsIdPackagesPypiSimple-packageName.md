# GET /api/v4/projects/{id}/packages/pypi/simple/*package_name

**Resource:** [Packages](../resources/Packages.md)
**The PyPi Simple Project Package Endpoint**
**Operation ID:** `getApiV4ProjectsIdPackagesPypiSimple*packageName`

This feature was introduced in GitLab 12.10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_name` | query | string | Yes | The PyPi package name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

