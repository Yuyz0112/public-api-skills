# PUT /allocations/{allocation_gid}

**Resource:** [Allocations](../resources/Allocations.md)
**Update an allocation**
**Operation ID:** `updateAllocation`

An existing allocation can be updated by making a PUT request on the URL for
that allocation. Only the fields provided in the `data` block will be updated;
any unspecified fields will remain unchanged.

Returns the complete updated allocation record.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The updated fields for the allocation.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully updated the allocation. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
