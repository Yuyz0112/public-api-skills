# GET /api/v4/projects/{id}/packages/conan/v1/users/check_credentials

**Resource:** [Packages](../resources/Packages.md)
**Check for valid user credentials per conan CLI**
**Operation ID:** `getApiV4ProjectsIdPackagesConanV1UsersCheckCredentials`

This feature was introduced in GitLab 12.4

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

