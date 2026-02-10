# GET /api/v4/groups/{id}/-/packages/debian/dists/*distribution/{component}/binary-{architecture}/Packages

**Resource:** [Packages](../resources/Packages.md)
**The binary files index**
**Operation ID:** `getApiV4GroupsIdDashPackagesDebianDists*distributionComponentBinary{architecture}Packages`

This feature was introduced in GitLab 13.5

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The group ID or full group path. |
| `distribution` | query | string | Yes | The Debian Codename or Suite |
| `component` | path | string | Yes | The Debian Component |
| `architecture` | query | string | Yes | The Debian Architecture |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 202 | Accepted |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

