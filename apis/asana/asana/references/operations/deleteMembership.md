# DELETE /memberships/{membership_gid}

**Resource:** [Memberships](../resources/Memberships.md)
**Delete a membership**
**Operation ID:** `deleteMembership`

A specific, existing membership for a `goal`, `project`, `portfolio` or `custom_field` can be deleted by making a `DELETE` request
on the URL for that membership.

Returns an empty data record.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully deleted the requested membership. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
