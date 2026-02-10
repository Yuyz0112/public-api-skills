# GET /api/v4/packages/maven/*path/{file_name}

**Resource:** [Packages](../resources/Packages.md)
**Download the maven package file at instance level**
**Operation ID:** `getApiV4PackagesMaven*pathFileName`

This feature was introduced in GitLab 11.6

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `path` | query | string | Yes | Package path |
| `file_name` | path | string | Yes | Package file name |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

