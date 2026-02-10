# GET /api/v4/group/{id}/-/packages/composer/p2/*package_name

**Resource:** [Packages](../resources/Packages.md)
**Composer v2 packages p2 endpoint at group level for package versions metadata**
**Operation ID:** `getApiV4GroupIdDashPackagesComposerP2*packageName`

This feature was introduced in GitLab 13.1

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

