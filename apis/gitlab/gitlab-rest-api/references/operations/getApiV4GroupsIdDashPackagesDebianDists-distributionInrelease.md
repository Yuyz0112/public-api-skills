# GET /api/v4/groups/{id}/-/packages/debian/dists/*distribution/InRelease

**Resource:** [Packages](../resources/Packages.md)
**The signed Release file**
**Operation ID:** `getApiV4GroupsIdDashPackagesDebianDists*distributionInrelease`

This feature was introduced in GitLab 13.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The group ID or full group path. |
| `distribution` | query | string | Yes | The Debian Codename or Suite |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

