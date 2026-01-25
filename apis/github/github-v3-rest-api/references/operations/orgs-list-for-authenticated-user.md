# GET /user/orgs

**Resource:** [orgs](../resources/orgs.md)
**List organizations for the authenticated user**
**Operation ID:** `orgs/list-for-authenticated-user`

List organizations for the authenticated user.

For OAuth app tokens and personal access tokens (classic), this endpoint only lists organizations that your authorization allows you to operate on in some way (e.g., you can list teams with `read:org` scope, you can publicize your organization membership with `user` scope, etc.). Therefore, this API requires at least `user` or `read:org` scope for OAuth app tokens and personal access tokens (classic). Requests with insufficient scope will receive a `403 Forbidden` response.

> [!NOTE]
> Requests using a fine-grained access token will receive a `200 Success` response with an empty list.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |

**Success Response Schema:**

Array of [organization-simple](../schemas/organization-simple/organization-simple.md)

