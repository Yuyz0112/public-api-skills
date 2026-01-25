# GET /user/packages/{package_type}/{package_name}/versions

**Resource:** [packages](../resources/packages.md)
**List package versions for a package owned by the authenticated user**
**Operation ID:** `packages/get-all-package-versions-for-package-owned-by-authenticated-user`

Lists package versions for a package owned by the authenticated user.

OAuth app tokens and personal access tokens (classic) need the `read:packages` scope to use this endpoint. For more information, see "[About permissions for GitHub Packages](https://docs.github.com/packages/learn-github-packages/about-permissions-for-github-packages#permissions-for-repository-scoped-packages)."

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `state` | query | enum: active, deleted | No | The state of the package, either active or deleted. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [package-version](../schemas/package-version/package-version.md)

