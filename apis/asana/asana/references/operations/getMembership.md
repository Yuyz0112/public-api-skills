# GET /memberships/{membership_gid}

**Resource:** [Memberships](../resources/Memberships.md)
**Get a membership**
**Operation ID:** `getMembership`

Returns a `project_membership`, `goal_membership`, `portfolio_membership`, or `custom_field_membership` record for a membership id.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved the record for a single membership. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
