# GET /api/v4/groups/{id}/-/packages/pypi/simple/*package_name

**Resource:** [Packages](../resources/Packages.md)
**The PyPi Simple Group Package Endpoint**
**Operation ID:** `getApiV4GroupsIdDashPackagesPypiSimple*packageName`

This feature was introduced in GitLab 12.10

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or full path of the group. |
| `package_name` | query | string | Yes | The PyPi package name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

