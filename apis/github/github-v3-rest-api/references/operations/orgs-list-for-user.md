# GET /users/{username}/orgs

**Resource:** [orgs](../resources/orgs.md)
**List organizations for a user**
**Operation ID:** `orgs/list-for-user`

List [public organization memberships](https://docs.github.com/articles/publicizing-or-concealing-organization-membership) for the specified user.

This method only lists _public_ memberships, regardless of authentication. If you need to fetch all of the organization memberships (public and private) for the authenticated user, use the [List organizations for the authenticated user](https://docs.github.com/rest/orgs/orgs#list-organizations-for-the-authenticated-user) API instead.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |

**Success Response Schema:**

Array of [organization-simple](../schemas/organization-simple/organization-simple.md)

