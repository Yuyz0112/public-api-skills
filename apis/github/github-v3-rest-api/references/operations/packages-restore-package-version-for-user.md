# POST /users/{username}/packages/{package_type}/{package_name}/versions/{package_version_id}/restore

**Resource:** [packages](../resources/packages.md)
**Restore package version for a user**
**Operation ID:** `packages/restore-package-version-for-user`

Restores a specific package version for a user.

You can restore a deleted package under the following conditions:
  - The package was deleted within the last 30 days.
  - The same package namespace and version is still available and not reused for a new package. If the same package namespace is not available, you will not be able to restore your package. In this scenario, to restore the deleted package, you must delete the new package that uses the deleted package's namespace first.

If the `package_type` belongs to a GitHub Packages registry that supports granular permissions, the authenticated user must have admin permissions to the package. For the list of these registries, see "[About permissions for GitHub Packages](https://docs.github.com/packages/learn-github-packages/about-permissions-for-github-packages#granular-permissions-for-userorganization-scoped-packages)."

OAuth app tokens and personal access tokens (classic) need the `read:packages` and `write:packages` scopes to use this endpoint. For more information, see "[About permissions for GitHub Packages](https://docs.github.com/packages/learn-github-packages/about-permissions-for-github-packages#permissions-for-repository-scoped-packages)."

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

