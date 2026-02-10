# GET /api/v4/projects/{id}/dependencies

**Resource:** [Dependency management](../resources/Dependency-management.md)
**Get a list of project dependencies**
**Operation ID:** `getApiV4ProjectsIdDependencies`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `package_manager` | query | any | No | Returns dependencies belonging to specified package managers: bundler, yarn, npm, pnpm, maven, composer, pip, conan, go, nuget, sbt, gradle, pipenv, poetry, setuptools, apk, conda, pub, cargo. |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesDependency](../schemas/APIEntitiesDependency/APIEntitiesDependency.md)

