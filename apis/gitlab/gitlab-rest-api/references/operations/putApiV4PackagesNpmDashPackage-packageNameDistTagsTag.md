# PUT /api/v4/packages/npm/-/package/*package_name/dist-tags/{tag}

**Resource:** [Packages](../resources/Packages.md)
**Create or Update the given tag for the given NPM package and version**
**Operation ID:** `putApiV4PackagesNpmDashPackage*packageNameDistTagsTag`

This feature was introduced in GitLab 12.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `tag` | path | string | Yes | Package dist-tag |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

