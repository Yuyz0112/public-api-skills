# GET /api/v4/projects/{id}/managed_licenses

**Resource:** [Licenses](../resources/Licenses.md)
**Get project software license policies**
**Operation ID:** `getApiV4ProjectsIdManagedLicenses`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesManagedLicense](../schemas/APIEntitiesManagedLicense/APIEntitiesManagedLicense.md)

