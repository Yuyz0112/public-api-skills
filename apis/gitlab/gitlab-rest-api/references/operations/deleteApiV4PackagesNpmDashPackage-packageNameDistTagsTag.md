# DELETE /api/v4/packages/npm/-/package/*package_name/dist-tags/{tag}

**Resource:** [Packages](../resources/Packages.md)
**Deletes the given tag**
**Operation ID:** `deleteApiV4PackagesNpmDashPackage*packageNameDistTagsTag`

This feature was introduced in GitLab 12.7

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `package_name` | query | string | Yes | Package name |
| `tag` | path | string | Yes | Package dist-tag |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |

