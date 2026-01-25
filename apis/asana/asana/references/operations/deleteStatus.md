# DELETE /status_updates/{status_update_gid}

**Resource:** [Status updates](../resources/Status-updates.md)
**Delete a status update**
**Operation ID:** `deleteStatus`

Deletes a specific, existing status update.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the specified status. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
