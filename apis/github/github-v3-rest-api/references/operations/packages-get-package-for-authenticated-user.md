# GET /user/packages/{package_type}/{package_name}

**Resource:** [packages](../resources/packages.md)
**Get a package for the authenticated user**
**Operation ID:** `packages/get-package-for-authenticated-user`

Gets a specific package for a package owned by the authenticated user.

OAuth app tokens and personal access tokens (classic) need the `read:packages` scope to use this endpoint. For more information, see "[About permissions for GitHub Packages](https://docs.github.com/packages/learn-github-packages/about-permissions-for-github-packages#permissions-for-repository-scoped-packages)."

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

[package](../schemas/package/package.md)

