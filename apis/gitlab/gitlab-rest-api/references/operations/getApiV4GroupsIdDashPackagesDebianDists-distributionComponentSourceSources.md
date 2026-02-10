# GET /api/v4/groups/{id}/-/packages/debian/dists/*distribution/{component}/source/Sources

**Resource:** [Packages](../resources/Packages.md)
**The source files index**
**Operation ID:** `getApiV4GroupsIdDashPackagesDebianDists*distributionComponentSourceSources`

This feature was introduced in GitLab 15.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The group ID or full group path. |
| `distribution` | query | string | Yes | The Debian Codename or Suite |
| `component` | path | string | Yes | The Debian Component |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 202 | Accepted |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

