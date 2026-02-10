# GET /api/v4/projects/{id}/packages/conan/v1/users/authenticate

**Resource:** [Packages](../resources/Packages.md)
**Authenticate user against conan CLI**
**Operation ID:** `getApiV4ProjectsIdPackagesConanV1UsersAuthenticate`

This feature was introduced in GitLab 12.2

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 404 | Not Found |

