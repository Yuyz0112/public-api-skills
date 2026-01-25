# DELETE /applications/{client_id}/token

**Resource:** [apps](../resources/apps.md)
**Delete an app token**
**Operation ID:** `apps/delete-token`

OAuth  or GitHub application owners can revoke a single token for an OAuth application or a GitHub application with an OAuth authorization.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 204 | Response |
| 422 | (reference) |

