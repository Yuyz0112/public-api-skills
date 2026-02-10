# GET /api/v4/projects/{id}/packages/debian/pool/{distribution}/{letter}/{package_name}/{package_version}/{file_name}

**Resource:** [Packages](../resources/Packages.md)
**Download Debian package**
**Operation ID:** `getApiV4ProjectsIdPackagesDebianPoolDistributionLetterPackageNamePackageVersionFileName`

This feature was introduced in GitLab 14.2

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `distribution` | path | string | Yes | The Debian Codename or Suite |
| `letter` | path | string | Yes | The Debian Classification (first-letter or lib-first-letter) |
| `package_name` | path | string | Yes | The Debian Source Package Name |
| `package_version` | query | string | Yes | The Debian Source Package Version |
| `file_name` | path | string | Yes | The Debian File Name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

