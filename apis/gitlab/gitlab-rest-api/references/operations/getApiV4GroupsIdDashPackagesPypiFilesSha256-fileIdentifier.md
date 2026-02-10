# GET /api/v4/groups/{id}/-/packages/pypi/files/{sha256}/*file_identifier

**Resource:** [Packages](../resources/Packages.md)
**Download a package file from a group**
**Operation ID:** `getApiV4GroupsIdDashPackagesPypiFilesSha256*fileIdentifier`

This feature was introduced in GitLab 13.12

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or full path of the group. |
| `file_identifier` | query | string | Yes | The PyPi package file identifier |
| `sha256` | path | string | Yes | The PyPi package sha256 check sum |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

