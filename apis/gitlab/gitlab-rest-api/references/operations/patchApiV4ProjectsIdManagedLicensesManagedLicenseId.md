# PATCH /api/v4/projects/{id}/managed_licenses/{managed_license_id}

**Resource:** [Licenses](../resources/Licenses.md)
**Update an existing software license policy from a project**
**Operation ID:** `patchApiV4ProjectsIdManagedLicensesManagedLicenseId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

**Success Response Schema:**

[APIEntitiesManagedLicense](../schemas/APIEntitiesManagedLicense/APIEntitiesManagedLicense.md)

