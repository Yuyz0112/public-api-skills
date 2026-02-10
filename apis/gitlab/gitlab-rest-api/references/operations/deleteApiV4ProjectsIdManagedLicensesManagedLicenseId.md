# DELETE /api/v4/projects/{id}/managed_licenses/{managed_license_id}

**Resource:** [Licenses](../resources/Licenses.md)
**Delete an existing software license policy from a project**
**Operation ID:** `deleteApiV4ProjectsIdManagedLicensesManagedLicenseId`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The ID or URL-encoded path of the project |

## Responses

| Status | Description |
|--------|-------------|
| 204 | No Content |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not found |

