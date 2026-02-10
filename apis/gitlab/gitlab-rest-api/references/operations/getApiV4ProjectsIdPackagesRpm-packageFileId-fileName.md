# GET /api/v4/projects/{id}/packages/rpm/*package_file_id/*file_name

**Resource:** [Packages](../resources/Packages.md)
**Download RPM package files**
**Operation ID:** `getApiV4ProjectsIdPackagesRpm*packageFileId*fileName`

This feature was introduced in GitLab 15.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_file_id` | query | integer | Yes | RPM package file id |
| `file_name` | query | string | Yes | RPM package file name |

## Responses

| Status | Description |
|--------|-------------|
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

