# POST /memberships

**Resource:** [Memberships](../resources/Memberships.md)
**Create a membership**
**Operation ID:** `createMembership`

Creates a new membership in a `goal`, `project`, `portfolio`, or `custom_field`, where members can be Teams or Users.

Returns the full record of the newly created membership.

## Request Body

The updated fields for the membership.

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created the requested membership. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
