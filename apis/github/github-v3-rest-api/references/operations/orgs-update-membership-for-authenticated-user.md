# PATCH /user/memberships/orgs/{org}

**Resource:** [orgs](../resources/orgs.md)
**Update an organization membership for the authenticated user**
**Operation ID:** `orgs/update-membership-for-authenticated-user`

Converts the authenticated user to an active member of the organization, if that user has a pending invitation from the organization.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |
| 422 | (reference) |

**Success Response Schema:**

[org-membership](../schemas/org-membership/org-membership.md)

