# PATCH /applications/{client_id}/token

**Resource:** [apps](../resources/apps.md)
**Reset a token**
**Operation ID:** `apps/reset-token`

OAuth applications and GitHub applications with OAuth authorizations can use this API method to reset a valid OAuth token without end-user involvement. Applications must save the "token" property in the response because changes take effect immediately. Invalid tokens will return `404 NOT FOUND`.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 422 | (reference) |

**Success Response Schema:**

[authorization](../schemas/authorization/authorization.md)

