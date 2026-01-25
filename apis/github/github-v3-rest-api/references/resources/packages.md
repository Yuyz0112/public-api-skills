# packages

Manage packages for authenticated users and organizations.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/orgs/{org}/docker/conflicts` | Get list of conflicting packages during Docker migration for organization | [View](../operations/packages-list-docker-migration-conflicting-packages-for-organization.md) |
| GET | `/orgs/{org}/packages` | List packages for an organization | [View](../operations/packages-list-packages-for-organization.md) |
| GET | `/orgs/{org}/packages/{package_type}/{package_name}` | Get a package for an organization | [View](../operations/packages-get-package-for-organization.md) |
| DELETE | `/orgs/{org}/packages/{package_type}/{package_name}` | Delete a package for an organization | [View](../operations/packages-delete-package-for-org.md) |
| POST | `/orgs/{org}/packages/{package_type}/{package_name}/restore` | Restore a package for an organization | [View](../operations/packages-restore-package-for-org.md) |
| GET | `/orgs/{org}/packages/{package_type}/{package_name}/versions` | List package versions for a package owned by an organization | [View](../operations/packages-get-all-package-versions-for-package-owned-by-org.md) |
| GET | `/orgs/{org}/packages/{package_type}/{package_name}/versions/{package_version_id}` | Get a package version for an organization | [View](../operations/packages-get-package-version-for-organization.md) |
| DELETE | `/orgs/{org}/packages/{package_type}/{package_name}/versions/{package_version_id}` | Delete package version for an organization | [View](../operations/packages-delete-package-version-for-org.md) |
| POST | `/orgs/{org}/packages/{package_type}/{package_name}/versions/{package_version_id}/restore` | Restore package version for an organization | [View](../operations/packages-restore-package-version-for-org.md) |
| GET | `/user/docker/conflicts` | Get list of conflicting packages during Docker migration for authenticated-user | [View](../operations/packages-list-docker-migration-conflicting-packages-for-authenticated-user.md) |
| GET | `/user/packages` | List packages for the authenticated user's namespace | [View](../operations/packages-list-packages-for-authenticated-user.md) |
| GET | `/user/packages/{package_type}/{package_name}` | Get a package for the authenticated user | [View](../operations/packages-get-package-for-authenticated-user.md) |
| DELETE | `/user/packages/{package_type}/{package_name}` | Delete a package for the authenticated user | [View](../operations/packages-delete-package-for-authenticated-user.md) |
| POST | `/user/packages/{package_type}/{package_name}/restore` | Restore a package for the authenticated user | [View](../operations/packages-restore-package-for-authenticated-user.md) |
| GET | `/user/packages/{package_type}/{package_name}/versions` | List package versions for a package owned by the authenticated user | [View](../operations/packages-get-all-package-versions-for-package-owned-by-authenticated-user.md) |
| GET | `/user/packages/{package_type}/{package_name}/versions/{package_version_id}` | Get a package version for the authenticated user | [View](../operations/packages-get-package-version-for-authenticated-user.md) |
| DELETE | `/user/packages/{package_type}/{package_name}/versions/{package_version_id}` | Delete a package version for the authenticated user | [View](../operations/packages-delete-package-version-for-authenticated-user.md) |
| POST | `/user/packages/{package_type}/{package_name}/versions/{package_version_id}/restore` | Restore a package version for the authenticated user | [View](../operations/packages-restore-package-version-for-authenticated-user.md) |
| GET | `/users/{username}/docker/conflicts` | Get list of conflicting packages during Docker migration for user | [View](../operations/packages-list-docker-migration-conflicting-packages-for-user.md) |
| GET | `/users/{username}/packages` | List packages for a user | [View](../operations/packages-list-packages-for-user.md) |
| GET | `/users/{username}/packages/{package_type}/{package_name}` | Get a package for a user | [View](../operations/packages-get-package-for-user.md) |
| DELETE | `/users/{username}/packages/{package_type}/{package_name}` | Delete a package for a user | [View](../operations/packages-delete-package-for-user.md) |
| POST | `/users/{username}/packages/{package_type}/{package_name}/restore` | Restore a package for a user | [View](../operations/packages-restore-package-for-user.md) |
| GET | `/users/{username}/packages/{package_type}/{package_name}/versions` | List package versions for a package owned by a user | [View](../operations/packages-get-all-package-versions-for-package-owned-by-user.md) |
| GET | `/users/{username}/packages/{package_type}/{package_name}/versions/{package_version_id}` | Get a package version for a user | [View](../operations/packages-get-package-version-for-user.md) |
| DELETE | `/users/{username}/packages/{package_type}/{package_name}/versions/{package_version_id}` | Delete package version for a user | [View](../operations/packages-delete-package-version-for-user.md) |
| POST | `/users/{username}/packages/{package_type}/{package_name}/versions/{package_version_id}/restore` | Restore package version for a user | [View](../operations/packages-restore-package-version-for-user.md) |
