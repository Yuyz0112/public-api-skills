# PUT /api/v4/groups/{id}/-/packages/npm/-/package/*package_name/dist-tags/{tag}

**Resource:** [Packages](../resources/Packages.md)
**Create or Update the given tag for the given NPM package and version**
**Operation ID:** `putApiV4GroupsIdDashPackagesNpmDashPackage*packageNameDistTagsTag`

This feature was introduced in GitLab 12.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the group |
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

