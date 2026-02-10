# GET /api/v4/groups/{id}/-/packages/debian/pool/{distribution}/{project_id}/{letter}/{package_name}/{package_version}/{file_name}

**Resource:** [Packages](../resources/Packages.md)
**Download Debian package**
**Operation ID:** `getApiV4GroupsIdDashPackagesDebianPoolDistributionProjectIdLetterPackageNamePackageVersionFileName`

This feature was introduced in GitLab 14.2

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The group ID or full group path. |
| `project_id` | path | integer | Yes | The Project Id |
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

