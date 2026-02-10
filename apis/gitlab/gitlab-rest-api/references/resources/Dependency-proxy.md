# Dependency proxy

Operations related to dependency proxy.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/projects/{id}/dependency_proxy/packages/npm/*package_name/-/*file_name` | Proxy the download of a NPM package tarball | [View](../operations/getApiV4ProjectsIdDependencyProxyPackagesNpm-packageNameDash-fileName.md) |
| GET | `/api/v4/projects/{id}/dependency_proxy/packages/maven/*path/{file_name}` | Proxy the download of a maven package file at a project level | [View](../operations/getApiV4ProjectsIdDependencyProxyPackagesMaven-pathFileName.md) |
| DELETE | `/api/v4/groups/{id}/dependency_proxy/cache` | Purge the dependency proxy for a group | [View](../operations/deleteApiV4GroupsIdDependencyProxyCache.md) |
