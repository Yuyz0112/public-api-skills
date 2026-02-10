# POST /api/v4/projects/{id}/managed_licenses

**Resource:** [Licenses](../resources/Licenses.md)
**Create a new software license policy in a project**
**Operation ID:** `postApiV4ProjectsIdManagedLicenses`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesManagedLicense](../schemas/APIEntitiesManagedLicense/APIEntitiesManagedLicense.md)

