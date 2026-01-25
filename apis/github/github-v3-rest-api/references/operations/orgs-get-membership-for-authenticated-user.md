# GET /user/memberships/orgs/{org}

**Resource:** [orgs](../resources/orgs.md)
**Get an organization membership for the authenticated user**
**Operation ID:** `orgs/get-membership-for-authenticated-user`

If the authenticated user is an active or pending member of the organization, this endpoint will return the user's membership. If the authenticated user is not affiliated with the organization, a `404` is returned. This endpoint will return a `403` if the request is made by a GitHub App that is blocked by the organization.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[org-membership](../schemas/org-membership/org-membership.md)

