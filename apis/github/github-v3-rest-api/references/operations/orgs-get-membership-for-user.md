# GET /orgs/{org}/memberships/{username}

**Resource:** [orgs](../resources/orgs.md)
**Get organization membership for a user**
**Operation ID:** `orgs/get-membership-for-user`

In order to get a user's membership with an organization, the authenticated user must be an organization member. The `state` parameter in the response can be used to identify the user's membership status.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

[org-membership](../schemas/org-membership/org-membership.md)

