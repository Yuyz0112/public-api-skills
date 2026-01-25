# PUT /memberships/{membership_gid}

**Resource:** [Memberships](../resources/Memberships.md)
**Update a membership**
**Operation ID:** `updateMembership`

An existing membership can be updated by making a `PUT` request on the membership. Only the fields provided in the `data` block will be updated;
any unspecified fields will remain unchanged. Memberships on `goals`, `projects`, `portfolios`, and `custom_fields` can be updated.

Returns the full record of the updated membership.

## Request Body

The membership to update.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully updated the requested membership. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**
