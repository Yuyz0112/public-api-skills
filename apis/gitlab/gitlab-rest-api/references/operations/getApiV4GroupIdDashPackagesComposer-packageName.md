# GET /api/v4/group/{id}/-/packages/composer/*package_name

**Resource:** [Packages](../resources/Packages.md)
**Composer packages endpoint at group level for package versions metadata**
**Operation ID:** `getApiV4GroupIdDashPackagesComposer*packageName`

This feature was introduced in GitLab 12.1

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of a group |
| `package_name` | query | string | Yes | The Composer package name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not Found |

