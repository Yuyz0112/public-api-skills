# DELETE /allocations/{allocation_gid}

**Resource:** [Allocations](../resources/Allocations.md)
**Delete an allocation**
**Operation ID:** `deleteAllocation`

A specific, existing allocation can be deleted by making a DELETE request on the URL for that allocation.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified allocation. |
| 400 | (reference) |
| 401 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
