# DELETE /api/v4/projects/{id}/packages/{package_id}

**Resource:** [Packages](../resources/Packages.md)
**Delete a project package**
**Operation ID:** `deleteApiV4ProjectsIdPackagesPackageId`

This feature was introduced in GitLab 11.9

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_id` | path | integer | Yes | The ID of a package |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 403 | Forbidden |
| 404 | Not Found |

