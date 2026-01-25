# GET /user/packages/{package_type}/{package_name}/versions/{package_version_id}

**Resource:** [packages](../resources/packages.md)
**Get a package version for the authenticated user**
**Operation ID:** `packages/get-package-version-for-authenticated-user`

Gets a specific package version for a package owned by the authenticated user.

OAuth app tokens and personal access tokens (classic) need the `read:packages` scope to use this endpoint. For more information, see "[About permissions for GitHub Packages](https://docs.github.com/packages/learn-github-packages/about-permissions-for-github-packages#permissions-for-repository-scoped-packages)."

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[package-version](../schemas/package-version/package-version.md)

