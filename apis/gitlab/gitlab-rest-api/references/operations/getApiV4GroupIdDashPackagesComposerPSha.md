# GET /api/v4/group/{id}/-/packages/composer/p/{sha}

**Resource:** [Packages](../resources/Packages.md)
**Composer packages endpoint at group level for packages list**
**Operation ID:** `getApiV4GroupIdDashPackagesComposerPSha`

This feature was introduced in GitLab 13.1

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of a group |
| `sha` | path | string | Yes | Shasum of current json |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not Found |

